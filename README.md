# Charts

- [x] PostgreSQL
- [ ] MySQL
- [ ] Redis
- [ ] RabbitMQ
- [ ] ChartMuseum

## PostgreSQL

### debug
```shell
helm upgrade --install --debug --dry-run --namespace=dev01 my-db1 ./postgres
```

### deploy
```shell
helm upgrade --install --create-namespace --wait --namespace=dev01 my-db1 ./postgres
```

### delete
```shell
helm delete --namespace=dev01 my-db1
```

## Redis

### debug
```shell
helm upgrade --install --debug --dry-run --namespace=dev02 redis1 ./redis
```

### deploy
```shell
helm upgrade --install --create-namespace --wait --namespace=dev02 redis1 ./redis
```

### delete
```shell
helm delete --namespace=dev02 redis1
```
