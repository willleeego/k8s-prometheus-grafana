# k8s-prometheus-grafana

```shell
kubectl apply -f  k8s-prometheus-grafana/node-exporter.yaml

kubectl apply -f  k8s-prometheus-grafana/prometheus/rbac-setup.yaml
kubectl apply -f  k8s-prometheus-grafana/prometheus/configmap.yaml 
kubectl apply -f  k8s-prometheus-grafana/prometheus/prometheus.deploy.yml 
kubectl apply -f  k8s-prometheus-grafana/prometheus/prometheus.svc.yml 

kubectl apply -f   k8s-prometheus-grafana/grafana/grafana-deploy.yaml
kubectl apply -f   k8s-prometheus-grafana/grafana/grafana-svc.yaml
kubectl apply -f   k8s-prometheus-grafana/grafana/grafana-ing.yaml


