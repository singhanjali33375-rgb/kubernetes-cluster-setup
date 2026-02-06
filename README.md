# kubernetes-cluster-setup
Step-by-step Kubernetes cluster setup using DevOps best practices, including node configuration, networking, and basic workload deployment.
Complete Folder & File Structure
kubernetes-cluster-setup/
│
├── README.md
├── .gitignore
│
├── scripts/
│   ├── install-docker.sh
│   ├── install-kubernetes.sh
│   └── cluster-init.sh
│
├── manifests/
│   ├── deployment.yaml
│   ├── service.yaml
│   └── namespace.yaml
│
├── terraform/          (optional – cloud setup)
│   ├── provider.tf
│   ├── main.tf
│   └── variables.tf
│
└── docs/
    └── cluster-architecture.png
    # Kubernetes Cluster Setup

This project demonstrates how to set up a Kubernetes cluster from scratch
using DevOps best practices. It includes node preparation, cluster initialization,
and deployment of sample workloads.

## Project Goals
- Set up Kubernetes master and worker nodes
- Configure container runtime
- Initialize Kubernetes cluster
- Deploy sample application on cluster

## Tech Stack
- Container Runtime: Docker
- Orchestration: Kubernetes
- Cloud / VM: AWS / Local VM
- IaC (optional): Terraform

## Architecture
User → Kubernetes Cluster → Pods → Services

## Project Structure
scripts/     - Installation & setup scripts manifests/   - Kubernetes YAML files terraform/   - Cloud infrastructure (optional) docs/        - Architecture diagrams
## Setup Steps
1. Prepare nodes (Linux VM / Cloud)
2. Install Docker
3. Install Kubernetes components
4. Initialize master node
5. Join worker nodes
6. Deploy application

## Kubernetes Components Used
- kubeadm
- kubelet
- kubectl
- Pod
- Deployment
- Service

## Sample Deployment
A sample application is deployed to verify the cluster setup.

## Future Enhancements
- Add Kubernetes Dashboard
- Implement RBAC
- Setup monitoring with Prometheus

## Author
Anjali Singh
