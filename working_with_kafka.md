kafka-console-producer.bat --broker-list localhost:9092 --topic test
kafka-console-consumer.bat --zookeeper localhost:2181 --topic test
cd Desktop/kafka_2.11-0.10.1.1/bin/windows
zkserver
kafka-topics.bat --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic test
.\bin\windows\kafka-server-start.bat .\config\server.properties