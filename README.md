# useful-docker-compose
Collection of useful docker-compose files for run services locally


## Single Zookeeper / Single Kafka

Run with:

docker-compose -f zookeeper-single-kafka-single.yml up
docker-compose -f zookeeper-single-kafka-single.yml down


## Multiple Zookeeper / Single Kafka


If you want to have three zookeeper nodes and experiment with zookeeper fault-tolerance.

Run with:

docker-compose -f zookeeper-multiple-kafka-multiple.yml up
docker-compose -f zookeeper-multiple-kafka-multiple.yml down