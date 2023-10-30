# KafkaApplication
1- start zookeeper:
under the bin/windows folder, execute this command:

	start zookeeper-server-start.bat D:\projects\Kafka\kafka_2.13-2.7.0\config\zookeeper.properties

2- start kafka server

	start kafka-server-start.bat D:\projects\Kafka\kafka_2.13-2.7.0\config\server.properties

3- start kafka consumer on the topic digitalcode

	kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic digitalcode --from-beginning
