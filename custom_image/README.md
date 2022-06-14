Download and unzip debezium-connector-mysql-1.7.2.zip in debezium-connector-mysql folder.

Run the docker build and push to docker registry

```
docker build -t quay.io/kahlai/connect-debezium:v4 .
docker push quay.io/kahlai/connect-debezium:v4
```

Replace the docker image in /openshift/KafkaConnect.yaml
