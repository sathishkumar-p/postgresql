# Install plain Postgresql on Kubernetes 

### Required:

1.  Kubernetes cluster v1.4+
2.  Minimum 1GB persistence volume
3.  kubectl 

```shell
cd db/k8s/
kubectl apply -f .  --namespace <<namespace-name>>
```