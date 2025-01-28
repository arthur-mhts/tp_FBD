# tp_FBD

## Start ZooKeeper
bin/zookeeper-server-start.sh config/zookeeper.properties

## Start Kafka
bin/kafka-server-start.sh config/server.properties

## Create topic 
bin/kafka-topics.sh --create --topic quickstart-events --bootstrap-server localhost:9092
