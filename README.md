#Work Technologies

Cassandra: NoSQL Distributed Database
(Partitoned row store - Data is read or written with a partition key)

Storing data in Cassandra: 

A Node represents a running instance of Cassandra. 
All data stored in Cassandra is associated with a "token"
V-Nodes (virtual nodes) take on a much smaller range of tokens

Schemaless- Items in a database do not need to have the same structure (Primary difference in NoSQL datbases compared to SQL)

You can ONLY retrieve items by their primary key in NoSQl databases

NoSQL - 1. "Not Only SQL" 2. Non-relational

=======================================================================================

Apache Kafka: A distributed messaging system for a vast amounts of data + Event streaming platform

Key Words: 

Producer - An application that sends data (messages) to Kafka

Consumer - An application that receives data from kafka 

Broker - Kafka Server

Cluster - Group of computers

Topic - A name for a Kafka stream

Partitions - Part of a topic

Offset - Unique id for a message within a partition 

Consumer groups - A group of consumers acting as a simple logical unit

Kakfa is run as a cluster of one or more servers that can span datacenters or cloud regions.
Some of these servers form the storage layer aka the brokers.
Other servers run Kafka Connect (used to import/export data as event streams)

Terminology:
Event - An event records the fact that "something happened" in the world or in your business. Ab event has a key, value, timestamp, and optional metadata headers

##Example:

##Event key: "Alice"
##Event value: "Made a payment of $200 to Bob"
##Event timestamp: "Jun. 25, 2020 at 2:06 p.m."

Producers: Producers are those client applications that publish (write) events to Kafka

Consumers: Consumers are those that subscribe to (read and process) these events

Topics: A topic is similar to a folder in a filesystem, and the events are the files in that folder. Topics are partitioned
-Every topic can be replicated to make your data fault-tolerant and highly-available (a common production setting is a replication of 3, which means three copies of data)

Partitioned: Meaning a topic is spread over a number of "buckets" located on different Kafka brokers

=======================================================================================

Spring Batch: An Open Source framework for Batch processing

Spring Batch is intended to work in conjunction with a scheduler rather than replace a scheduler.



