![oci schema for my k3s cluster](./k3s-oci-schema.svg)

# Configuring your cluster

## Install ArgoCD on your cluster

```bash
$ kubectl create namespace argocd && kubectl apply -n argocd -f argocd.yaml
```
> ArgoCD v2.7.9
