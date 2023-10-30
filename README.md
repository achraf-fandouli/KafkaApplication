# KafkaApplication
1- start zookeeper:
under the bin/windows folder, execute this command:

	start zookeeper-server-start.bat D:\projects\Kafka\kafka_2.13-2.7.0\config\zookeeper.properties

2- start kafka server

	start kafka-server-start.bat D:\projects\Kafka\kafka_2.13-2.7.0\config\server.properties

3- start kafka consumer on the topic digitalcode

	kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic digitalcode --from-beginning

4- Zookeeper, kafka server and kafka consumer: 
<img width="950" alt="Zookeeper-Kafka server-Consumer" src="https://github.com/achraf-fandouli/KafkaApplication/assets/55927202/25ad2164-3355-4745-8a48-eb5372eda723">

5- API with Kafka:

<img width="637" alt="API with Kafka" src="https://github.com/achraf-fandouli/KafkaApplication/assets/55927202/32dc6a14-8c68-4157-8178-122ec9507a0f">
