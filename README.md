# helm-charts

debug
```shell
helm upgrade --install --debug --dry-run --create-namespace --wait --namespace=dev01 postgres ./postgres
```

deploy
```shell
helm upgrade --install --create-namespace --wait --namespace=dev01 postgres ./postgres
```

delete
```shell
helm delete --namespace=dev01 postgres
```
