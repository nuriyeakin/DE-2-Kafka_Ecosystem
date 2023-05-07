# QUESTIONS

### 1.  
Create a topic named `atscale`, 2 partitions and replication factor 1.

### 2. 
List all topics.

### 3. 
Describe `atscale` topic.

### 4. 
Use data-generator and send `https://raw.githubusercontent.com/erkansirin78/datasets/master/Churn_Modelling.csv` to  3 patitioned `churn` topic.

- Message key should be CustomerId.

- Consume under `churn_group` and this group must have 3 consumer. 
    - Use different terminal for each consumer. 
    - Use `kafka-console-consumer.sh` as a consumer.


### 5. 
Delete `atscale` and `churn` topics.


### 6.
-  Using Python Kafka do the following tasks:
    - Produce the names of Turkey's geographical regions to a topic you specify, using the numbers you specify at the beginning of each of them as keys. For example, 1 Marmara, 2 Aegean.
    - With the Consumer, print the key, value, partition, timestamp information as following example.
```
Key: 1, Value: Marmara, Partition: 0, TS: 1613224639352 
Key: 4, Value: İç Anadolu, Partition: 1, TS: 1613224654849 
Key: 3, Value: Akdeniz, Partition: 2, TS: 1613224661486 
Key: 2, Value: Ege, Partition: 2, TS: 1613224667044
```
