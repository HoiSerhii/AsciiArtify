# Comparison of Kubernetes Cluster Deployment Tools

|| Minikube | Kind | K3d |
| --- | --- | --- | --- |
| Description | This is a local Kubernetes system that allows you to deploy a Kubernetes cluster on a single computer. Deploy as a VM, a container, or on bare-metal | Kind (Kubernetes in Docker) is a tool for running local Kubernetes clusters using Docker container "nodes". | K3d is a lightweight tool for running Kubernetes clusters using Docker containers using the Rancher Kubernetes Engine (RKE). |
| OS | Cross-platform (Linux, macOS, Windows) | Depend on Docker, in general Cross-platform (Linux, macOS, Windows) |  Depend on Docker, in general Cross-platform (Linux, macOS, Windows) |
| Pros |  |  | - Easy to set up and use<br>- Lightweight and fast |
| Cons | - Limited scalability<br>- Can be resource-intensive<br>- Requires manual configuration for some features | - Can be resource-intensive<br>- Not recommended for production use | - Not recommended for production use |

# Demonstration

# Conclusions
For our PoC we will use K3d