# Port forward to access ArgoCD UI
kubectl port-forward svc/argocd-server -n argocd 8080:443