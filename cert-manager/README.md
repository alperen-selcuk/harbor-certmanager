## cert-manager install 

install with single manifest

```
kubectl apply -f https://github.com/cert-manager/cert-manager/releases/latest/download/cert-manager.yaml
```

after that apply clusterissuer for sign you certificates 

```
kubectl apply -f issuer.yaml
```
