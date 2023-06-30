# Comparison of Kubernetes Cluster Deployment Tools

|| Minikube | Kind | K3d |
| --- | --- | --- | --- |
| Description | This is a local Kubernetes system that allows you to deploy a Kubernetes cluster on a single computer. Deploy as a VM, a container, or on bare-metal | Kind (Kubernetes in Docker) is a tool for running local Kubernetes clusters using Docker container "nodes". | K3d is a lightweight tool for running Kubernetes clusters using Docker containers using the Rancher Kubernetes Engine (RKE). |
| OS | Cross-platform (Linux, macOS, Windows) | Depend on Docker, in general Cross-platform (Linux, macOS, Windows) |  Depend on Docker, in general Cross-platform (Linux, macOS, Windows) |
| Cluster startup time | 29,448 s | 19,691 s | 15,576 s |
| Cluster tear-down time | 2,616 s | 0,805 s | 0,700 s |
| Cluster resource consumptions | minikube with docker (CPUs=8, Memory=15681 MiB):CPU: ~20% Memory Usage: ~680.8 MiB | (CPUs=8, Memory=15681 MiB): CPU: ~20% Memory Usage: ~581 MiB | (CPUs=8, Memory=15681 MiB): CPU: ~20% Memory Usage: ~502 MiB |
| Popularity | 25.8k stars on GitHub | 11.1k stars on GitHub | 4.1k stars on GitHub |

# Demonstration

# Conclusions
For our PoC we will use K3d