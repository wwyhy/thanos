# thanos and Prometheus Deployment

Refer to https://github.com/thanos-io/kube-thanos/tree/main/examples/all/manifests

1. Deploy Thanos
  * $ cd thanos
  * $ kubectl apply -f .
2. Deploy Pormetheus
  * $ helm install prometheus-operator prometheus-community/kube-prometheus-stack -n monitoring-system -f prom-operator-value.yaml
