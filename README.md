# BLUEAKIO Docker

这是 BLUEAKIO 维护的 Docker 镜像 & Docker Compose 项目存储库

## Koishi

因为官方在“在容器中使用”只给了 Docker 指令以及 Podman 指令的部署方式，所以就弄了个 Docker Compose 文件来做另一个部署方式

### 使用方法
```
curl -o docker-compose.yml https://raw.githubusercontent.com/BLUEAKIO/docker/main/Koishi/docker-compose.yml
docker compose up -d
```

或使用 Jsdelivr CDN 加速
```
curl -o docker-compose.yml https://fastly.jsdelivr.net/gh/BLUEAKIO/docker@main/Koishi/docker-compose.yml
docker compose up -d
```

也可使用 BLUEAKIO 的 GitHub 文件加速服务
```
curl -o docker-compose.yml https://gh-proxy.blueakio.com/https://raw.githubusercontent.com/BLUEAKIO/docker/main/Koishi/docker-compose.yml
docker compose up -d
```

默认部署在 `./koishi` 目录下，如需调整部署位置，请自行修改 `docker-compose.yml`

##