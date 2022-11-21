# pnpm docker image

基于 node:16 & node:16-alpine3.14

## 打镜像并上传 Dockerhub
```shell
# 执行前 docker login 成功
./build-node-16.sh
./build-node-16-alpine.sh
```

## 使用

https://hub.docker.com/r/chf007/pnpm

```shell
docker pull chf007/pnpm
docker pull chf007/pnpm:7.17.0-alpine
```

