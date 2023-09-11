# rancher-cluster

Helm Chart to deploy a job to register a cluster in Rancher

supported values:

```yaml
image: ghcr.io/mcsps/utils:latest

rancher:
  url: https://127.0.0.1
  apitoken: 1234567 ## optional, or provide a secret (see below)
```


```yaml
apiVersion: v1
data:
  APITOKEN: MTIzNDU=
kind: Secret
metadata:
  name: apitoken
```
