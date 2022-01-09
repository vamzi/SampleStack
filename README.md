# CraftDemoTerraform
[![pipeline status](https://gitlab.com/c4780/craftdemoterraform/badges/main/pipeline.svg)](https://gitlab.com/c4780/craftdemoterraform/-/commits/main)

This project will manage CD of the carftdemoapp helm chart to AWS EKS using terraform

EKS Internal Service Architecture

```
ArgoCD - GitOps
Prometheus Stack, Grafana - Monitoring
Traffic Manager - Telepresnece
Istio - Ingress
Metrics-Server - For metrics HPA
```

Helm release of ArgoCD will deploy all the above stack