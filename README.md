# Repository containing Kubernetes manifests and ArgoCD configuration for Web Applications
# Allows for automated cluster deployment upon pushed changes monitored by ArgoCD

## /apps - Contains Kubernetes manifests/deployment configurations for apps
## /argocd - Defines ArgoCD configurations for apps managed within pipeline
## /monitoring(private) - Contains deployment/routing configuration for monitoring services such as Prometheus and Grafana
## /networking(private) - Contains deployment configuration for NGINX-ingress controller sidecar'ed with Cloudflared tunnel