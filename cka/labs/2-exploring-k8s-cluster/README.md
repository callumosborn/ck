# Exploring a Kubernetes Cluster with kubectl

## Description

You are working for BeeBox, a company that provides regular shipments of bees to customers. The company is in the process of building a Kubernetes-based infrastructure for some of their software.

You have several work tickets that will need to be addressed by using kubectl to interact with the Kubernetes cluster. You will need to collect some information from the cluster and save that information in some files for later review. You will also need to make some changes to the cluster.

## Learning Objectives

- Get a List of Persistent Volumes Sorted by Capacity

Use kubectl to get a list of persistent volumes. Ensure this list is sorted by the persistent volume capacity. Store the sorted kubectl output in the file /home/cloud_user/pv_list.txt.

- Run a Command Inside the `quark` Pod's Container to Obtain a Key Value

Locate the quark pod within the beebox-mobile namespace. Run a command inside this pod's container to obtain a key value. The key value is located inside the container's file system in a file called /etc/key/key.txt. Save the key value to a file on the Kube control plane server at /home/cloud_user/key.txt.

- Create a Deployment Using a Spec File

You will find a deployment spec file located at /home/cloud_user/deployment.yml. Using this file, create the deployment it describes in the cluster.

- Delete the `beebox-auth` Service

There is a service in the beebox-mobile namespace called beebox-auth-svc. Delete this service.