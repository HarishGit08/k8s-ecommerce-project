# Monitoring

Prometheus and Grafana were installed using Helm.

Install commands:

helm repo add prometheus-community https://prometheus-community.github.io/helm-charts

helm install monitoring prometheus-community/kube-prometheus-stack \
--namespace monitoring
