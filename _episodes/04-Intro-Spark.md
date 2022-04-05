---
title: "Introduction to Spark"
time: 0

objectives:
- "Spark introduction"
- "RDD"
---

<img width="627" alt="Screen Shot 2022-04-05 at 10 14 13 AM" src="https://user-images.githubusercontent.com/47697537/161813040-79e2bae1-dcf8-4f90-ac45-2484ffa0a0ea.png">

- The beginning of Spark
Originator: Matei Zaharia. Start in 2009 as a class project in UC Berkeley’s  AMPlab. Need to do machine learning faster on HDFS

- Doctoral dissertation (2013)
http://www.eecs.berkeley.edu/Pubs/TechRpts/2014/EECS-­‐2014-­‐12.pdf

- Hear Matei talking
https://www.youtube.com/watch?v=BFtQrfQ2rn0

- What is Spark?

A general execution engine to improve/replace  MapReduce. Spark’s operators are a superset of  MapReduce

- What’s wrong with the  original MapReduce?

Limitations of MapReduce.
- Originated around year 2000. Old technology.
- Designed for batch-processing large amount of  webpages in Google
- And it does that job very well!

- Not ﬁt for
- Complex, multi-passing algorithms. 
- Interactive ad-hoc queries
- Real‐time stream processing

<img width="297" alt="Screen Shot 2022-04-05 at 10 18 47 AM" src="https://user-images.githubusercontent.com/47697537/161813677-7da8fda2-c0bd-4b59-b7ee-4e95f9330eae.png">

<img width="291" alt="Screen Shot 2022-04-05 at 10 19 05 AM" src="https://user-images.githubusercontent.com/47697537/161813723-624b5aa3-ec5e-4fc9-9982-19e5c0967565.png">


- Core Spark data abstraction
- Resilient Distributed Dataset (RDD)

<img width="558" alt="image" src="https://user-images.githubusercontent.com/47697537/161813841-aff0c17e-99d4-473b-a227-88d00c704d13.png">

RDD — Resilient Distributed Dataset

The features of RDDs (decomposing the name):
- Resilient, i.e. fault-tolerant, so able to recompute missing or damaged partitions due to node failures.
- Distributed with data residing on multiple nodes in a cluster.
- Dataset is a collection of partitioned data with primitive values or values of values, e.g. tuples or other objects (that represent records of the data you work with).

<img width="469" alt="image" src="https://user-images.githubusercontent.com/47697537/161814158-451c2e93-f301-4d5c-9705-f777596f7b2b.png">

Lazy execution

<img width="402" alt="image" src="https://user-images.githubusercontent.com/47697537/161814243-8c9747be-a0ad-439b-9c17-54b5414bcc2b.png">



