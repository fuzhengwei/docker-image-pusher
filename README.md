# 镜像仓库使用方法

[**images.txt**](https://github.com/fuzhengwei/docker-image-pusher/blob/main/images.txt)

```java
mysql:8.0.32
phpmyadmin:5.2.1
redis:6.2
spryker/redis-commander:0.8.0
rabbitmq:3.12.9
```

1. 在 `images.txt` 添加你需要的镜像（PR方式提交），你可以从 [https://hub.docker.com/](https://hub.docker.com/) 搜索需要的镜像后添加。
2. 新添加镜像，需要等待1分钟同步。之后通过命令 `docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysql` 拉取你需要的镜像，如果有版本号，可以添加。如；`mysql:8.0.32`
