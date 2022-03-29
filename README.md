# pnpm docker image

基于 node:16 & node:16-alpine3.14

## 打镜像并上传 Dockerhub
```shell
# 执行前 docker login 成功
./build-node-16.sh
./build-node-16-alpine.sh
```

## 使用
```shell
docker pull chf007/pnpm
docker pull chf007/pnpm:6.32.3-alpine
```

