# thanos and Prometheus Deployment

1. Deploy Thanos
  * $ cd thanos
  * $ kubectl apply -f .
2. Deploy Pormetheus
  * $ helm install prometheus-operator prometheus-community/kube-prometheus-stack -n monitoring-system -f prom-operator-value.yaml
