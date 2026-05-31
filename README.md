# AZURE-ACS-AKS-LAB
Configuring and Securing Azure Container Registry (ACR) and Azure Kubernetes Service (AKS) using RBAC, Managed Identities, and secure networking.

##Overview:
Configuring and Securing Azure Container Registry (ACR) and Azure Kubernetes Service (AKS). The lab focuses on deploying and securing containerized applications in Azure by integrating ACR with AKS, implementing Azure RBAC, and using Managed Identities for secure authentication.

Throughout the lab, a private container registry is created to store container images, an AKS cluster is deployed to host workloads, and role assignments are configured to allow secure image retrieval from ACR. The lab also demonstrates how to expose applications through both public and internal load balancers, highlighting key networking and security considerations for Kubernetes environments.

(The project was completed as part of hands-on preparation for the AZ-500: Azure Security Engineer Associate certification).

##Objectives:


##Technologies used:
- Microsoft Azure – Cloud platform used to deploy and manage all resources.
- Azure Container Registry (ACR) – Private container image registry for storing and managing Docker images.
- Azure Kubernetes Service (AKS) – Managed Kubernetes platform for deploying and orchestrating containerized applications.
- Azure Role-Based Access Control (RBAC) – Access management system used to control permissions for Azure resources.
- Managed Identities for Azure Resources – Secure authentication mechanism that eliminates the need for stored credentials.
- Azure Virtual Network (VNet) – Provides network isolation and connectivity for AKS resources.
- Azure Load Balancer – Used to expose Kubernetes services internally and externally.
- Kubernetes – Container orchestration platform used to manage application deployments and services.
- Docker – Containerization technology used to package application workloads.
- Azure CLI – Command-line tool used to provision and manage Azure resources.
- kubectl – Kubernetes command-line tool used to interact with the AKS cluster.
- YAML – Configuration language used for Kubernetes deployments and service definitions

