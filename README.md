# lz-argocd-applications

## Install

`kubectl apply -f <argo application yaml`

The order of install does not matter.

**Example**:

- `kubectl apply -f kong-app.yaml`
- `kubectl apply -f argo-workflows.yaml`
- `kubectl apply -f argo-rollouts.yaml`
- `kubectl apply -f datadog.yaml`

## Uninstall

`kubectl delete -f <argo application yaml>`

**Example**:

- `kubectl delete -f kong-app.yaml`
- `kubectl delete -f argo-workflows.yaml`
- `kubectl delete -f argo-rollouts.yaml`
- `kubectl delete -f datadog.yaml`
