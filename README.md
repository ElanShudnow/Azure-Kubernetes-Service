# Azure Kubernetes Service
A place to share all the Azure Kubernetes Cluster scenarios I have tested, documented, and automated. 

For additional Azure content, visit my other content which includes

* My blog: [https://www.shudnow.io](https://www.shudnow.io)
* AzureCode GitHub Repository: [https://www.github.com/elanshudnow/AzureCode](https://www.github.com/elanshudnow/AzureCode)


# Scenarios

| Scenario | Description |
| --------------- | --------------- |
| [net00-cni-overlay-public-cluster-managed-vnet](https://github.com/ElanShudnow/Azure-Kubernetes-Service/tree/main/net00-cni-overlay-public-cluster-managed-vnet) | Learn about AKS CNI Overlay Public Clusters with an AKS Managed Virtual Network.  Learn what goes into planning a CNI Overlay Cluster, what the configuration looks like, and use my Azure CLI Scrapbook to deploy. A public AKS Cluster is where the API Server is reachable via the internet. |
| [net01-cni-overlay-public-cluster-custom-vnet](https://github.com/ElanShudnow/Azure-Kubernetes-Service/tree/main/net01-cni-overlay-public-cluster-custom-vnet ) | Learn about AKS CNI Overlay Public Clusters with a Custom Virtual Network.  Learn what goes into planning a CNI Overlay Cluster, what the configuration looks like, and use my Azure CLI Scrapbook to deploy. A public AKS Cluster is where the API Server is reachable via the internet. |
| [net02-cni-overlay-private-cluster-managed-vnet](https://github.com/ElanShudnow/Azure-Kubernetes-Service/tree/main/net02-cni-overlay-private-cluster-managed-vnet) | Learn about AKS CNI Overlay Private Clusters with an AKS Managed Virtual Network.  Learn what goes into planning a CNI Overlay Cluster, what the configuration looks like, and how Private DNS Connectivity using a managed Private DNS Zone functions all deployable via my Azure CLI Scrapbook.  A private AKS Cluster is where the API Server is unreachable via the internet and without [API Server VNET Integration](https://learn.microsoft.com/en-us/azure/aks/api-server-vnet-integration), is only reachable via Private Endpoints / Private DNS Zones. |
| [net03-cni-overlay-private-cluster-custom-vnet-system-pe](https://github.com/ElanShudnow/Azure-Kubernetes-Service/tree/main/net03-cni-overlay-private-cluster-custom-vnet-system-pe) | Learn about AKS CNI Overlay Private Clusters with an AKS Custom Virtual Network. The Private Endpoint will be leveraging system mode in which the AKS Cluster will manage the Private DNS Zone and Private Endpoint. Learn what goes into planning a CNI Overlay Cluster, what the configuration looks like, and how Private DNS Connectivity using a managed Private DNS Zone functions all deployable via my Azure CLI Scrapbook.  A private AKS Cluster is where the API Server is unreachable via the internet and without [API Server VNET Integration](https://learn.microsoft.com/en-us/azure/aks/api-server-vnet-integration), is only reachable via Private Endpoints / Private DNS Zones.  |