.. _rancher:

Step Zero: Kubernetes on Bare Metal using `Rancher 2.x <https://rancher.com/docs/rancher/v2.x/en/>`_
----------------------------------------------------------------------------------------------------

We're going to create our own Kubernetes cluster on existing servers (which could actually be
on-premise bare-metal servers or on-premise virtual machines) using
`Rancher 2.x <https://rancher.com/docs/rancher/v2.x/en/>`_ for creating and managing the cluster
and its workloads.

We will create a Single Node Installation of Rancher and then use it to create a Kubernetes Cluster
running the Rancher Kubernetes Engine (RKE) using as many nodes as you like, need or have.

**Prerequisites:**

- **Rancher Server:**
  - One machine for running Rancher Server (`Requirements <https://rancher.com/docs/rancher/v2.x/en/installation/requirements/>`_)
  - `Docker Engine <https://docs.docker.com/install/#supported-platforms>`_
  - `Port Requirements <https://rancher.com/docs/rancher/v2.x/en/installation/references/>`_

- **Rancher Launched Kubernetes:**
  - A number of machines that will become the Kubernetes Cluster
