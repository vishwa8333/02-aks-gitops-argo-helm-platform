# AKS GitOps Platform with Argo CD and Helm

## Goal

Deploy a production-style Kubernetes platform on Azure Kubernetes Service using GitOps, Helm charts, ingress, secrets, and monitoring.

## Azure Services

- Azure Kubernetes Service
- Azure Container Registry
- Azure Key Vault
- Azure Monitor
- Managed Identity
- Application Gateway or NGINX Ingress

## DevOps Skills Demonstrated

- Kubernetes platform engineering
- GitOps with Argo CD
- Helm chart management
- Container image delivery
- Secret management with Key Vault CSI
- Blue-green or canary deployment patterns

## Suggested Structure

```text
terraform/
helm/
apps/
argocd/
manifests/
.github/workflows/
```

## Commands

```powershell
az aks get-credentials --resource-group rg-aks-platform --name aks-platform
kubectl get nodes
helm list -A
```

