# pnpm docker image

基于 node:16 & node:16-alpine3.14

基于 node:20 & node:20-alpine3.18

## 打镜像并上传 Dockerhub
```shell
# 执行前 docker login 成功
./build-node-16.sh
./build-node-16-alpine.sh

./build-node-20.sh
./build-node-20-alpine.sh
```

## 使用

https://hub.docker.com/r/chf007/pnpm

```shell
# current latest=8.14.1-node-20
docker pull chf007/pnpm

docker pull chf007/pnpm:8.14.1-node-16
docker pull chf007/pnpm:8.14.1-node-16-alpine

docker pull chf007/pnpm:8.14.1-node-20
docker pull chf007/pnpm:8.14.1-node-20-alpine
```

