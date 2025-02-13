# Access the bookinfo app on CRC

```bash
kubectl port-forward service/bookinfo-gateway-istio -n bookinfo 8080:80
```
