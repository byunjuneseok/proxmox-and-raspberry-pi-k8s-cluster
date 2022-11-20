# Monitoring

## Prometheus
```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm install --namespace monitoring kube-prometheus-stack prometheus-community/kube-prometheus-stack -f prometheus.yaml
```

