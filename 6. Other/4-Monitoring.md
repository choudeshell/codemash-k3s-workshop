# Monitoring

## Getting Started

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
```

```
kubectl create ns monitoring
helm -n monitoring install prometheus-stack prometheus-community/kube-prometheus-stack
 ```

## Clean Up
```
helm uninstall prometheus-stack
```