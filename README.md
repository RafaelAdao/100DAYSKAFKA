# 100 Days Of Kafka

Link to the challenge: [100 Days Of Kafka](https://developer.confluent.io/100-days-of-code)

## Log

### Day 0: January 22, 2024

**Today's Progress**: Followed the quickstart guide to setup a cluster on Confluent Kafka, and created a topic and produced and consumed messages.

![image](https://github.com/RafaelAdao/100DAYSKAFKA/assets/5923706/0716ee58-d93b-48fd-8c93-d91bf5cb1ad5)

**Thoughts**: It's not my first contact with Kafka, but I will commit to this challenge to learn more about it.

### Day 1: January 23, 2024

**Today's Progress**: I watched the video of the concept of a Event on Kafka, on this [link](https://developer.confluent.io/courses/apache-kafka/events).

**Thoughts**: The video is just an introduction to the concept of an event on Kafka. Each event is a key/value object, stored in a topic partition. The key is used to identify the partition, and the value is the data itself. The events are immutable, and the order is guaranteed within a partition. The value can be any type of data, JSON, JSON Schema, Avro, etc. The events are stored in a log, and the consumer can read the events from the beginning, or from a specific offset.

### Day 2: January 24, 2024

**Today's Progress**: Kafka topics are ordered, immutable, append-only logs. Topics can be created using the command line or the Kafka API. We can also list, describe, and delete topics. Topics can be configured with a retention period, a number of partitions, and a replication factor.

**Thoughts**: Kafka topics are the core of the Kafka architecture. They are the place where all events are stored. Is not like a traditional queue, where messages are deleted after being consumed. Kafka topics are append-only logs, which means that messages are never deleted.

### Day X: Y Z, 2024

**Today's Progress**: 

**Thoughts**: 
