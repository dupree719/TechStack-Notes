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

Key Words: (What makes up Kafka)

Producer - An application that sends data (messages) to Kafka (Producers are those client applications that publish (write) events to Kafka)

Consumer - An application that receives data from kafka (Consumers are those that subscribe to (read and process) these events)

Broker - Kafka Server

Cluster - Group of computers

Topic - A name for a Kafka stream

Partitions - Part of a topic (Kafka stream)

Offset - Unique id for a message within a partition 

Consumer groups - A group of consumers acting as a simple logical unit

Kakfa is run as a cluster of one or more servers (computers) that can span datacenters or cloud regions.
Some of these servers form the storage layer aka the brokers.
Other servers run Kafka Connect (used to import/export data as event streams)


Event - An event records the fact that "something happened" in the world or in your business. Ab event has a key, value, timestamp, and optional metadata headers


Use Cases- 

Real-time data processing: Kafka is often used to collect and process large streams of data in real-time. This can include things like tracking website visitors, analyzing log files, and processing sensor data.

Streaming data integration: Kafka can be used to integrate data from multiple sources and make it available in real-time to downstream systems. For example, a company might use Kafka to combine data from a variety of source systems (e.g. CRM, ERP, marketing automation) and make it available to a data warehouse or data lake for analysis.

Event-driven architectures: Kafka can be used to build event-driven architectures, where different parts of a system can react to changes in the data stream in real-time. This can include things like triggering a workflow, sending a notification, or updating a database.

LinkedIn: LinkedIn, now owned by Microsoft, uses Kafka as the backbone of its data infrastructure. Kafka is used to handle more than 1 trillion messages per day, and it plays a critical role in LinkedIn's data pipeline, data processing and data integration.

Netflix: Netflix uses Kafka to handle its real-time data streams. The platform uses Kafka to collect data from a variety of sources and make it available to downstream systems for analysis and action.

Uber: Uber uses Kafka as a key component of its data pipeline. The platform uses Kafka to collect data from a variety of sources and make it available to downstream systems for analysis and action.

=======================================================================================

Spring Batch is a lightweight, comprehensive framework for developing batch applications. It provides a robust set of features for handling the complex and bulk-processing of data.

Spring Batch uses a modular and extensible architecture, which allows developers to easily create, test, and maintain batch jobs.

Spring Batch provides built-in support for reading and writing data in a variety of formats, such as CSV, XML, and fixed-width files, as well as reading data from and writing data to relational databases.

Spring Batch jobs are defined using a simple XML configuration file, which allows for easy setup and maintenance of batch jobs.

Spring Batch provides various types of batch processing, including chunk-based processing, tasklet-based processing, and partitioning for scaling batch jobs.

Spring Batch provides robust error handling, including transaction management, retry, and skippable exception classes, which makes it easy to handle errors and exceptions that may occur during batch processing.

Spring Batch is built on top of the Spring Framework, so it is able to leverage the features provided by Spring, such as dependency injection, and it can easily integrate with other Spring projects.

Spring Batch provides testing support through Spring Batch Test, which makes it easy to write unit and integration tests for batch jobs.

Spring Batch can be run as standalone application or within a container such as Spring Boot Application

Spring Batch provides monitoring and management support through Spring Batch Admin and the Spring Batch JMX, which makes it easy to monitor and manage batch jobs.


