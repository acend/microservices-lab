# Docker Images


## Public Images

Following Images are used

* docker.io/postgres:13
* docker.io/grafana/grafana:latest (tested with 10.2.3)
* quay.io/prometheus/prometheus:latest (v2.22.2?)
* quay.io/prometheus/alertmanager:latest
* quay.io/jaegertracing/all-in-one:1.24.0
* quay.io/debezium/postgres:13
* quay.io/debezium/zookeeper:2.3


## Lab Images

Following Lab specific images are used


### 2 Mini-Monolith

* quay.io/acend/microservices-lab-monolith-application:latest


### 3 Microservices Rest

* quay.io/acend/microservices-lab-rest-order:latest-step-3.5 (Solution Step 3.5)
* quay.io/acend/microservices-lab-rest-order:latest (Final Solution including LRA)
* quay.io/acend/microservices-lab-rest-stock:latest (including LRA)


### 4. Event Driven Architecture

* quay.io/acend/microservices-lab-kafka-order:latest
* quay.io/acend/microservices-lab-kafka-stock:latest
* quay.io/acend/microservices-lab-debezium-kafka:latest
* quay.io/acend/microservices-lab-kafka-viewer:latest


### 5. Debezium with Outbox Pattern

* quay.io/acend/microservices-lab-debezium-order:latest
* quay.io/acend/microservices-lab-debezium-stock:latest
* quay.io/acend/microservices-lab-debezium-connect:latest
* quay.io/acend/microservices-lab-debezium-viewer:latest
* quay.io/acend/microservices-lab-debezium-kafka:latest
