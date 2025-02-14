# 镜像仓库使用方法

[**images.txt**](https://github.com/fuzhengwei/docker-image-pusher/blob/main/images.txt)

```java
portainer:latest
mysql:8.0.32
phpmyadmin:5.2.1
redis:6.2
redis:7.2
redis-commander:0.8.0
rabbitmq:3.12.9
rocketmq:5.1.0
skywalking-oap-server:9.3.0
skywalking-ui:9.3.0
rocketmq:5.1.0
nginx:1.25.1
prometheus:2.47.2
grafana:10.2.0
canal-server:v1.1.6、v1.1.7
canal-adapter:v1.1.6
elasticsearch:7.17.14
kibana:7.17.14
zookeeper:3.9.0
xxl-job-aarch64:2.4.0
xxl-job-admin:2.4.0
nacos-server:v2.2.3-slim
kafka:3.7.0
kafka-eagle:3.0.2
logstash:7.14.2
registry:latest
sentinel-dashboard:1.8.7
mysqld-exporter:v0.15.1
redis_exporter:alpine-amd64
redis_exporter:alpine-arm64
redis_exporter:v1.62.0
node-exporter:v1.8.2
alpine:3.20.1
jenkins:2.439
fatedier/frps:v0.60.0 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/frps:v0.60.0
fatedier/frpc:v0.60.0 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/frpc:v0.60.0
neowitch/moneyprinterturbo:latest -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/moneyprinterturbo:latest
ankane/pgvector:v0.5.0 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/pgvector:v0.5.0
ollama/ollama:0.5.10 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/ollama:0.5.10
```

1. 在 `images.txt` 添加你需要的镜像（PR方式提交），你可以从 [https://hub.docker.com/](https://hub.docker.com/) 搜索需要的镜像后添加。
2. 新添加镜像，需要等待1分钟同步。之后通过命令 `docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysql` 拉取你需要的镜像，如果有版本号，可以添加。如；`mysql:8.0.32`

```yml
mysql:
  image: registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysql:8.0.32
  container_name: mysql
  command: --default-authentication-plugin=mysql_native_password
  restart: always
  environment:
    TZ: Asia/Shanghai
    MYSQL_ROOT_PASSWORD: 123456
  ports:
    - "13306:3306"
  volumes:
    - ./mysql/my.cnf:/etc/mysql/conf.d/mysql.cnf:ro
    - ./mysql/sql:/docker-entrypoint-initdb.d
  healthcheck:
    test: [ "CMD", "mysqladmin" ,"ping", "-h", "localhost" ]
    interval: 5s
    timeout: 10s
    retries: 10
    start_period: 15s
```

---

- 参考仓库 [@tech-shrimp/docker_image_pusher](https://github.com/tech-shrimp/docker_image_pusher)
