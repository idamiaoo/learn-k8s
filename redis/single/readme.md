###

1. 创建 redis配置 configMap
```shell
kubectl create -f redis-config.yaml 
```

2. 创建存储pv,pvc
```shell
kubectl create -f redis-storage.yaml 
```

3. 创建 service 和 pod
```shell
kubectl create -f redis-deploy.yaml
```