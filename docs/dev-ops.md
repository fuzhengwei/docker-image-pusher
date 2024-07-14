# DevOps

## 1. 设置镜像地址

```java
sudo mkdir -p /etc/docker
sudo tee /etc/docker/daemon.json <<-'EOF'
{
"registry-mirrors": [
"https://dc.j8.work"
],
"insecure-registries":["116.198.201.187:5000"]
}
EOF
sudo systemctl daemon-reload
sudo systemctl restart docker
```

## 2. 私有仓库常用命令

### 2.1 查看私有镜像仓库中存在的镜像文件

```java
[root@lavm-cnqkgk85q4 ~]# curl 116.198.201.187:5000/v2/_catalog
{"repositories":["kafka","kafka-eagle","mysql","phpmyadmin","redis","registry"]}
```

### 2.2 查看指定的镜像版本

```java
[root@lavm-cnqkgk85q4 ~]# curl 116.198.201.187:5000/v2/redis/tags/list
{"name":"redis","tags":["6.2","latest"]}
```

### 2.3 拉取镜像

```java
docker pull 116.198.201.187:5000/redis
docker pull 116.198.201.187:5000/redis:6.2
docker pull 116.198.201.187:5000/redis:latest
```

- 从私有的镜像仓库拉取镜像文件。

### 2.4 推送镜像

```java
docker push 116.198.201.187:5000/mysql:latest
```

- 推送镜像，这个命令很有用，后面在 GitHub Actions 中会使用到。
