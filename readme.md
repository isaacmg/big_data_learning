# Big Data Guide 
Hey everyone this is an informal repository where I discus Big Data technologies. It originally a rose out of my notes that I took while learning about various things. For the most part I will be focusing on Open Source Technologies and Big Data Systems design although I will briefly describe some other things. If you see anything incorrect or anything that should be added feel free to fork and make a pull request. 
## Introduction and a brief history
![big_data](https://upload.wikimedia.org/wikipedia/commons/7/7c/Hilbert_InfoGrowth.png =100x100)
### The Origins of Big Data
The term Big Data most likely originated sometime in the 1990s (you can see one of the earliest PDFs on the subject [here](http://static.usenix.org/event/usenix99/invited_talks/mashey.pdf)). The term emerged in response to the growing size of data sets and the need for non-traditional methods of processing them. 
### The Birth of Hadoop 
Hadoop originates from the Google File System paper which was published in 2003 and 
## Principals 
### Basic elements of a data pipeline
Various use cases will differ however, most big data pipelines will have similar common features. For the most part they will follow the following form:   
1. Data Collection
2. Ingestion from a data source (this may also been called the extraction phase)
2. Transformation/Computation
3. (Not always but most of the time) storage 
4. Serving the data to the user
This could involve either providing 
### Examples: 
Reccomendation engine: [See a real example here by Comcast here:] https://spark-summit.org/2015-east/wp-content/uploads/2015/03/SSE15-18-Neumann-Alla.pdf  
1. Users watch various movies and rate them. 
2. Rating data is stored in HDFS and watch/click data is generated in realtime in log files.
3. Data sources are combined and fed into a pretrained reccomendation engine.
4. Recommendations are stored and pushed back to the user. 

## Distributed Computing 
### HDFS 

### Spark 
#### PySpark 
Find Spark is very useful for finding PySpark on your installation if you run in to problems. You can get it here https://github.com/minrk/findspark.

### Flink

#### Installing Flink on Windows 
See https://ci.apache.org/projects/flink/flink-docs-release-0.8/local_setup.html first. 
#### Flink vs Spark
A lot of people have debated whether they should use Spark or Flink. Here are a few articles and slideshows that discus the differences:
http://www.infoworld.com/article/2919602/hadoop/flink-hadoops-new-contender-for-mapreduce-spark.html
http://stackoverflow.com/questions/28082581/what-is-the-difference-between-apache-spark-and-apache-flink
http://www.slideshare.net/sbaltagi/flink-vs-spark
## Databases 
### NoSQL
#### Graph Databases
**Neo4j**
## Messaging/ Real time Streaming Data

## Deploying, managing, creating Machine learning models 

## Data Visiualization 
http://www.slideshare.net/BenLaird/real-time-data-viz-with-spark-streaming-kafka-and-d3js
##
https://www.sigmoid.com/integrating-spark-kafka-hbase-to-power-a-real-time-dashboard/
https://kafka-summit.org
## Hardware
Setting up your own small Hadoop cluster 
http://www.oneillscrossing.com/home-built-hadoop-analytics-cluster/#Hardware_310_per_node
## Workflow Software 
### Nifi 
### Airflow 
Attention if you install Airflow with pip you will have to find the base directory pip installed it to. In my case it was \usr\local\lib\python2.7\dist-packages\airflow
## Languages 
### Python 
### Scala 
### Java 
### R 