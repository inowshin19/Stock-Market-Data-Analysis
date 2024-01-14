# Stock-Market-Data-Analysis

This work have different parts. At first, some data which are already stored in a csv file is used.

Data: https://datahub.io/core/nasdaq-listings#resource-nasdaq-listed

Kafka and zookeeper is used along with Amazon EC2 to produce data and consume the data. Thus, in this way, Kafka takes the data from CSV file to produce that and the consumer consumes the data and sends it to Amazon S3 bucket. 

Amazon Glue and Crawler are used to crawl data from S3 bucket and to query data from Amazon S3 bucket. 
