# 镜像仓库使用方法

[**images.txt**](https://github.com/fuzhengwei/docker-image-pusher/blob/main/images.txt)

| 序号 | 原始                              | 代理                                                         |
| ---- | --------------------------------- | ------------------------------------------------------------ |
| 1    | portainer:latest                  | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/portainer:latest |
| 2    | mysql:8.0.32                      | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysql:8.0.32 |
| 3    | mysql:8.4.4                       | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysql:8.4.4 |
| 4    | phpmyadmin:5.2.1                  | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/phpmyadmin:5.2.1 |
| 5    | redis:6.2                         | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/redis:6.2 |
| 6    | redis:7.2/7.4.13                  | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/redis:7.2/7.4.13 |
| 7    | redis-commander:0.8.0             | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/redis-commander:0.8.0 |
| 8    | rabbitmq:3.12.9                   | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/rabbitmq:3.12.9 |
| 9    | rocketmq:5.1.0                    | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/rocketmq:5.1.0 |
| 10   | skywalking-oap-server:9.3.0       | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/skywalking-oap-server:9.3.0 |
| 11   | skywalking-ui:9.3.0               | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/skywalking-ui:9.3.0 |
| 12   | nginx:1.25.1                      | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/nginx:1.25.1 |
| 13   | prometheus:2.47.2                 | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/prometheus:2.47.2 |
| 14   | grafana:10.2.0                    | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/grafana:10.2.0 |
| 15   | canal-server:v1.1.6               | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/canal-server:v1.1.6 |
| 16   | canal-server:v1.1.7               | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/canal-server:v1.1.7 |
| 17   | canal-adapter:v1.1.6              | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/canal-adapter:v1.1.6 |
| 18   | elasticsearch:7.17.14\7.17.28     | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/elasticsearch:7.17.14\7.17.28 |
| 19   | kibana:7.17.14\7.17.28            | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/kibana:7.17.14\7.17.28 |
| 20   | zookeeper:3.9.0                   | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/zookeeper:3.9.0 |
| 21   | xxl-job-aarch64:2.4.0             | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/xxl-job-aarch64:2.4.0 |
| 22   | xxl-job-admin:2.4.0               | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/xxl-job-admin:2.4.0 |
| 23   | nacos-server:v2.2.3-slim          | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/nacos-server:v2.2.3-slim |
| 24   | kafka:3.7.0                       | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/kafka:3.7.0 |
| 25   | kafka-eagle:3.0.2                 | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/kafka-eagle:3.0.2 |
| 26   | logstash:7.14.2\7.17.28           | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/logstash:7.14.2\7.17.28 |
| 27   | registry:latest                   | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/registry:latest |
| 28   | sentinel-dashboard:1.8.7          | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/sentinel-dashboard:1.8.7 |
| 29   | mysqld-exporter:v0.15.1           | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysqld-exporter:v0.15.1 |
| 30   | redis_exporter:alpine-amd64       | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/redis_exporter:alpine-amd64 |
| 31   | redis_exporter:alpine-arm64       | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/redis_exporter:alpine-arm64 |
| 32   | redis_exporter:v1.62.0            | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/redis_exporter:v1.62.0 |
| 33   | node-exporter:v1.8.2              | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/node-exporter:v1.8.2 |
| 34   | alpine:3.20.1                     | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/alpine:3.20.1 |
| 35   | jenkins:2.439                     | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/jenkins:2.439 |
| 36   | fatedier/frps:v0.60.0             | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/frps:v0.60.0 |
| 37   | fatedier/frpc:v0.60.0             | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/frpc:v0.60.0 |
| 38   | neowitch/moneyprinterturbo:latest | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/moneyprinterturbo:latest |
| 39   | ankane/pgvector:v0.5.0            | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/pgvector:v0.5.0 |
| 40   | ollama/ollama:0.5.10              | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/ollama:0.5.10 |
| 41   | dpage/pgadmin4:9.1.0              | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/pgadmin4:9.1.0 |
| 42   | n8nio/n8n:1.88.0                  | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/n8n:1.88.0 |
| 43   | pgvector/pgvector:pg17            | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/pgvector:pg17 |
| 44   | apache/hadoop:2.10.2              | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/hadoop:2.10.2 |
| 45   | node:18-alpine                    | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/node:18-alpine |
| 46   | node:20-alpine                    | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/node:20-alpine |
| 47   | openjdk:8-jre-slim                | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/openjdk:8-jre-slim |
| 48   | openjdk:17-jdk-slim               | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/openjdk:17-jdk-slim |
| 49   | openjdk:17-ea-17-jdk-slim-buster  | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/openjdk:17-ea-17-jdk-slim-buster |
| 50   | mcp/grafana:latest                | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mcp/grafana:latest |
| 51   | postgres:14.18                    | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/postgres:14.18 |
| 52   | httpsok/nginx:1.28.0-alpine       | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/nginx:1.28.0-alpine |
| 53   | nacos/nacos-server:v3.1.1         | docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/nacos-server:v3.1.1  |

```java
portainer:latest
mysql:8.0.32
mysql:8.4.4 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/mysql:8.4.4
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
dpage/pgadmin4:9.1.0 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/pgadmin4:9.1.0
n8nio/n8n:1.88.0 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/n8n:1.88.0
pgvector/pgvector:pg17 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/pgvector:pg17
apache/hadoop:2.10.2 -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/hadoop:2.10.2
openjdk:8-jre-slim -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/openjdk:8-jre-slim
node:18-alpine -> docker pull registry.cn-hangzhou.aliyuncs.com/xfg-studio/node:18-alpine
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
