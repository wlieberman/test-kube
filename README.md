# Test-Kube Repo

This repo contains a test ingress controller and a basic apache 'Hello-World!' site

For the ingress-controller to work, you must label your proxy node with `node-role: proxy`
Example:

```bash
kubectl label node my-proxy node-role=proxy
```
