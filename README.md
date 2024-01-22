# tp_JEE_kafka

# commandes 

C:\Tools\kafka_2.13-3.6.1>start bin\windows\zookeeper-server-start.bat config/zookeeper.properties

C:\Tools\kafka_2.13-3.6.1>start bin\windows\kafka-server-start.bat config/server.properties

C:\Tools\kafka_2.13-3.6.1>start bin/kafka-console-consumer.sh --bootstrap-server localhost:9092 --topic R4 --property print.key=true --property print.value=true --property key.deserializer=org.apache.kafka.common.serialization.StringDeserializer --property value.deserializer=org.apache.kafka.common.serialization.LongDeserializer
