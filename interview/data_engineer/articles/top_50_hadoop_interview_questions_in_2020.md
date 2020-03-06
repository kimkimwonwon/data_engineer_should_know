# Top 50 Hadoop Interview Questions In 2020

1. What are the basic differences between relational database and HDFS?

|                         | RDBMS   | Hadoop  |
| :---:                   | :---    | :---    |
|Data Types               |RDBMS relies on the structured data and the schema of the data is always known.|Any kind of data can be stored into Hadoop i.e. Be it structured, unstructured or semi-structured.|
|Processing               |RDBMS provides limited or no processing capabilities.|Hadoop allows us to process the data which is distributed across the cluster in a parallel fashion.|
|Schema on Read Vs. Write |RDBMS is based on ‘schema on write’ where schema validation is done before loading the data.|On the contrary, Hadoop follows the schema on read policy.|
|Read/Write Speed         |In RDBMS, reads are fast because the schema of the data is already known.|The writes are fast in HDFS because no schema validation happens during HDFS write.|


3. What is Hadoop and its components. 
- Storage unit– HDFS (NameNode, DataNode)
- Processing framework– YARN (ResourceManager, NodeManager)

4. What are HDFS and YARN?

- HDFS
  - HDFS (Hadoop Distributed File System) is the storage unit of Hadoop. It is responsible for storing different kinds of data as blocks in a distributed environment. It follows master and slave topology.














