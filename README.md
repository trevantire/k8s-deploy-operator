# K8s Deploy Operator

Kubernetes operator for automated deployment workflows.

## Components
- Custom Resource Definitions (CRDs)
- Reconciliation controller
- Helm chart for installation

## Deploy
```bash
helm install deploy-operator ./charts/deploy-operator
kubectl apply -f examples/deploy-cr.yaml
```
