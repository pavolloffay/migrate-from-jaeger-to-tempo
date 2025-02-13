# Service Mesh

The manifests in this folder deploy service mesh.

## Access the bookinfo app on CRC

```bash
kubectl port-forward service/bookinfo-gateway-istio -n bookinfo 8080:80
```

## Notes

This manifests are based on https://developers.redhat.com/articles/2024/09/16/how-use-gateway-api-openshift-service-mesh-26?source=sso#deploy_the_sample_application