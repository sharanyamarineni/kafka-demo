# kafka-demo

Download kafka and unzip

### start zookeeper

bin/zookeeper-server-start.sh config/zookeeper.properties

### start kafka server

bin/kafka-server-start.sh config/server.properties

### create kafka topic

bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic Kafka_Example

