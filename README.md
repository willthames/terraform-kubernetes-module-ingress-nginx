```
helm repo add ingress-nginx/ingress-nginx https://kubernetes.github.io/ingress-nginx
helm repo update
helm template ingress-nginx ingress-nginx/ingress-nginx \
  --namespace ingress-nginx \
  --values values.yaml \
  --output-dir base
```
