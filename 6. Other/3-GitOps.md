# ArgoCD - Declarative GitOps CD for Kubernetes

## Getting Started

```bash
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

```bash
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d; echo
```

```bash
kubectl port-forward svc/argocd-server -n argocd 8080:443
```

## New App

>Application Name: guestbook
>Repository URL: https://github.com/choudeshell/guestbook
>Path: guestbook
>Namespace: guestbook


## Cleanup
```
kubectl delete -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```
