# Big Data Notes 
Hey everyone this is an informal repository where I discus Big Data technologies. It originally a rose out of my notes that I took while learning about various things. For the most part I will be focusing on Open Source Technologies and Big Data Systems design although I will briefly describe some other things. If you see anything incorrect or anything that should be added feel free to fork and make a pull request. 
## Introduction and a brief history
### The Origins of Big Data
### The Birth of Hadoop 
Hadoop was originates from the Google File System paper which was published in 2003 and 
## Principals 
### Basic elements of a data pipeline
Various use case will differ however, most big data pipelines will have similar common features. Data pipelines can get vary complicated very quickly so we will describe a very simple example to start.  
1. Data Collection
2. Ingestion from a data source (this may also been called the Extraction phase)
Your pipeline will almost always start with ingestion of from some sort of data source. In most cases the data source will be some sort of database (or assortment of databases), however it could also come from a sensor or directly from the user.
2. Transformation/Computation
3. Storing the data 
4. Serving the data to the user
This could involve either providing 
### Examples: 
Movie reccomendation: [See real example here] https://spark-summit.org/2015-east/wp-content/uploads/2015/03/SSE15-18-Neumann-Alla.pdf  
1. Users watch various movies and rate them. 
2. Rating data is stored in HDFS and watch/click data is generated in realtime in log files.
3. Data is combined with user viewing history 
3.
## Languages 
### Python 
### Scala 
### Java 
### R 
## Distributed Computing 
### Spark 
#### PySpark 
Find Spark is very useful for finding PySpark on your installation if you run in to problems. You can get it here https://github.com/minrk/findspark.
## Messaging/Streaming Data 
### Flink

#### Installing Flink on Windows 
See https://ci.apache.org/projects/flink/flink-docs-release-0.8/local_setup.html first. 
#### Flink vs Spark
http://www.infoworld.com/article/2919602/hadoop/flink-hadoops-new-contender-for-mapreduce-spark.html
http://stackoverflow.com/questions/28082581/what-is-the-difference-between-apache-spark-and-apache-flink
http://www.slideshare.net/sbaltagi/flink-vs-spark
## Databases 
### NoSQL
#### Graph Databases
**Neo4j** 
## Machine Learning 
## Data Visiualization 
http://www.slideshare.net/BenLaird/real-time-data-viz-with-spark-streaming-kafka-and-d3js
##
https://www.sigmoid.com/integrating-spark-kafka-hbase-to-power-a-real-time-dashboard/
https://kafka-summit.org
##
Setting up your own small Hadoop cluster 
http://www.oneillscrossing.com/home-built-hadoop-analytics-cluster/#Hardware_310_per_node