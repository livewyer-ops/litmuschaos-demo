# litmuschaos-demo

## Install litmuschaos

```
helm repo add litmuschaos https://litmuschaos.github.io/litmus-helm/
kubectl create ns litmus
helm install chaos litmuschaos/litmus --namespace=litmus
```
