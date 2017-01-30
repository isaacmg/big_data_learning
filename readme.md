# Big Data Guide 
## Table of Contents  

* [Introduction and History](#intro)  
   * [Origins of Big Data](#orgins)
   * [The Birth of Hadoop](#hadoopbirth)
* [Principals](#principals)
* [Cluster Computing Systems](#cluster)
  * [HDFS](#hdfs)
  * [MapReduce](#MapReduce)
  * [Spark](#spark)
  * [Flink](#flink)

  
Hey everyone this is an informal repository where I discus Big Data technologies. It originally a rose out of my notes that I took while learning about various things. For the most part I will be focusing on Open Source Technologies and Big Data Systems design although I will briefly describe some other things. If you see anything incorrect or anything that should be added feel free to fork and make a pull request.
<a name="intro"/>
## Introduction and a brief history
<img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Hilbert_InfoGrowth.png" width=200px height=200px></img>
<a name="orgins"/>
### The Origins of Big Data
The term Big Data most likely originated sometime in the 1990s (you can see one of the earliest PDFs on the subject [here](http://static.usenix.org/event/usenix99/invited_talks/mashey.pdf)). The term emerged in response to the growing size of data sets and the need for non-traditional methods of processing them. 
<a name="hadoopbirth"/>
### The Birth of Hadoop 
Hadoop originates from the Google File System paper which was published in 2003 and 
<a name="principals"/>
## Principals

### MapReduce, YARN, HDFS and Hadoop

### Basic elements of a data pipeline
Various use cases will differ however, most big data pipelines will have similar common features. For the most part they will follow the following form:

1. Data Collection
2. Ingestion from a data source (this may also been called the extraction phase)
2. Transformation/Computation
3. (Not always but most of the time) storing data  
4. Serving the data to the user

### Real World Architectures 
In practice it is usually much more complicated than this. You are often extracting data from multiple sources and combining it into one, you have several machine learning models which you train offline and need deploy etc.

[IBM Series on Big Data](http://www.ibm.com/developerworks/library/bd-archpatterns3/index.html?ca=drs-)
#### Lambda Architecture 

### Examples: 
**Reccomendation engine**:
Simple example:

1. Users watch various movies and rate them. 
2. Rating data is stored in a database and watch/click data is generated in realtime in log files.
3. Data sources are combined and fed into a pretrained reccomendation engine.
4. Recommendations are stored and pushed back to the user. 

Real world examples: 

◦ [Spotify Movie Reccomendations with Spark](http://www.slideshare.net/MrChrisJohnson/collaborative-filtering-with-spark)

◦ [Comcast TV recommendations](https://spark-summit.org/2015-east/wp-content/uploads/2015/03/SSE15-18-Neumann-Alla.pdf)

◦ [Netflix Movie reccomendations with Spark and GraphX](http://www.slideshare.net/SessionsEvents ehtsham-elahi-senior-research-engineer-personalization-science-and-engineering-group-at-netflix-at-mlconf-sea-50115?next_slideshow=1) (mainly machine learning focused, but still interesting)

◦ [Caserta Movie Reccomendations](http://www.slideshare.net/CasertaConcepts/analytics-week-recommendations-on-spark)

◦ [Computering Reccomendations at scale with Flink](http://data-artisans.com/computing-recommendations-at-extreme-scale-with-apache-flink/)


** Monitoring ** 

Hospital Example: 
1.
[Monitoring Traffic Data]("https://www.mapr.com/blog/monitoring-real-time-uber-data-using-spark-machine-learning-streaming-and-kafka-api-part-1")
<a name="cluster" />
## Distributed Computing 
### Modern HDFS 
### MapReduce
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
## Messaging/ Real time streaming data
### Flume 
### Kafka 

## Creating, training, deploying, and managing, machine learning models 

## Data Visualization 
http://www.slideshare.net/BenLaird/real-time-data-viz-with-spark-streaming-kafka-and-d3js
https://www.sigmoid.com/integrating-spark-kafka-hbase-to-power-a-real-time-dashboard/

## Diffrences between Data Science, Data Engineering, Business Intelligence, and Software Engineering 
[The Rise of the Data Engineer on Medium](https://medium.freecodecamp.com/the-rise-of-the-data-engineer-91be18f1e603#.7v0hp99i0)

[Differences between job positions](https://bigdatauniversity.com/blog/data-scientist-vs-data-engineer/)
## Hardware
### GPUs and Big Data 
[Overview]("http://www.nvidia.com/object/data-science-analytics-database.html")
[GPUs and Big Data]("http://www.hpl.hp.com/techreports/2009/HPL-2009-38.pdf")
### Setting up a Hadoop Cluster
[Setting up your own small Hadoop cluster] (http://www.oneillscrossing.com/home-built-hadoop-analytics-cluster/#Hardware_310_per_node)
## Workflow Software 
### Nifi 
### Airflow 
Attention if you install Airflow with pip you will have to find the base directory pip installed it to. In my case it was \usr\local\lib\python2.7\dist-packages\airflow
## Languages 
### Python 
### Scala 
### Java 
### R 

## Resources 
### Conferences
[Open Data Science](http://opendatascience.com)
[Flink Forward](http://flink-forward.org)
[Kafka Summit](https://kafka-summit.org)
[Rec Systems](https://recsys.acm.org)
[Spark Summit](https//spark-summit.org)
### Interesting Blogs
[PaddleSoft](http://medium.com/@paddlesoft)
[Netflix](http://http://techblog.netflix.com)
[Uber](http://https://eng.uber.com)
### Courses
### Books 
