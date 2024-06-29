# Kafka quick-start guide

### Start Kafka with Kraft

1. find kafka

    which kafka-storage.sh 

2. generate storage uid

    ~/kafka_2.13-3.7.0/bin/kafka-storage.sh random-uuid

3. format storage

    ~/kafka_2.13-3.7.0/bin/kafka-storage.sh format -t <storage_uuid> -c ~/kafka_2.13-3.7.0/config/kraft/server.properties

4. start kafka

    ~/kafka_2.13-3.7.0/bin/kafka-server-start.sh ~/kafka_2.13-3.7.0/config/kraft/server.properties

- end of output should contain info for server:
![alt text](<Pasted Graphic.png>)
￼
### Run kafka-topics.sh command with already set $path
![run kafka-topics.sh](image.png)