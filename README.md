# kafka-commands

## Kafka Commands used:

- Command used for "Start the ZooKeeper service" is mentioned below:
- .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

-  Command used for "Run Kafka Service"  is mentioned below:
- .\bin\windows\kafka-server-start.bat .\config\server.properties

- Command used for create, list, topics  is mentioned below:
- .\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --create --topic Dog-Tuffy
- .\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --list

-  Command used to "Run Kafka Producer" (will provide a > prompt for writing messages)  is mentioned below:
- .\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic Dog-Tuffy 

-  Command used to "Run Kafka Consumer" (to show messages from the beginning)  is mentioned below:
- .\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic Dog-Tuffy --from-beginning

