# docker

Some docker-compose files for use in my projects

### Kafka - http://localhost:9003
```shell
docker compose -f docker-compose_kafka.yml -p kafka up -d
```

### Redis
```shell
docker compose -f docker-compose_redis.yml -p redis up -d
```

### OpenSearch - http://localhost:5601
```shell
docker compose -f docker-compose_opensearch.yml -p opensearch up -d
```

### MongoDB
```shell
docker compose -f docker-compose_mongodb.yml -p mongodb up -d
```

### PostGres
```shell
docker compose -f docker-compose_postgres.yml -p postgres up -d
```

### SonarQube
```shell
docker compose -f docker-compose_sonarqube.yml -p sonar up -d
```
