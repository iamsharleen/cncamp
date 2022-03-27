# cncamp

Commands
```
k -apply -f simple-deploy.yaml

k -apply -f istio-specs.yaml

k get svc -n istio-system
# istio-ingressgateway   LoadBalancer   10.106.248.79

curl -H "Host: simple.cncamp.io"  10.106.248.79/healthz
# working
```
