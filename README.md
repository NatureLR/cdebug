# cdebug

## docker

```shell
docker run -d --restart=unless-stopped --name cdebug -p 80:80  uhub.service.ucloud.cn/naturelr/cdebug
```

## k8s

```shell
kubectl apply -f https://raw.githubusercontent.com/NatureLR/cdebug/master/k8s.yaml
```
