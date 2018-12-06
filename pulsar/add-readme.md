
# Pulsar 

Apache Pulsar is an open-source distributed pub-sub messaging system originally created at Yahoo and now part of the Apache Software Foundation.

Pulsar's key features include:

Native support for multiple clusters in a Pulsar instance, with seamless geo-replication of messages across clusters
Very low publish and end-to-end latency
Seamless scalability out to over a million topics
A simple client API with bindings for Java, Python, and C++
Multiple subscription modes for topics (exclusive, shared, and failover)
Guaranteed message delivery with persistent message storage provided by Apache BookKeeper
A serverless lightweight computing framework Pulsar Functions offers stream native data processing.
A serverless connector framework Pulsar IO built on-top-of Pulsar Functions to make moving data in and out Apache Pulsar easier.
Tiered Storage offloads data from hot/warn storage to cold/longterm storage (such as S3 and GCS) when the data is aging out.


## Chart Details
This chart bootstraps a [Pulsar](https://pulsar.apache.org/docs/en/pulsar-2.0/)  deployment. The chart has the following components,
- Apache Pulsar
- Zookeeper

This chart is mmaintained by Ravikumar Sanjay Muthiyalu (github: muthiyalu) 
