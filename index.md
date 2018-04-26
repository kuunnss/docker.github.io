## Linux Docker Demo

### 1.安装docker

···
sudo apt install docker.io
···

### 2.查看docker版本
```
sudo docker -v
```

### 3.配置 Docker 加速器
使用 Docker 的时候，需要经常从官方获取镜像，但是由于显而易见的网络原因，拉取镜像的过程非常耗时，严重影响使用 Docker 的体验。

···
curl -sSL https://get.daocloud.io/daotools/set_mirror.sh | sh -s http://91221545.m.daocloud.io
···

### 4.输出Hello World
```
sudo docker run Hello-World
```

### 5.安装并运行nginx
```
sudo docker --name mynginx -d -p 8080:80 ngnix
```
访问 localhost:8080 就能看到页面了

