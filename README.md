# harbor-certmanager

## DNS config

first you need to create an A record DNS validation. after that you should helm install.

## cert-manager 

install harbor use helm with values.yaml in repository
you can customize for yourself.

```
helm repo add harbor https://helm.goharbor.io
helm repo update
helm install harbor harbor/harbor -f values.yaml -n harbor --create-namespace
```
