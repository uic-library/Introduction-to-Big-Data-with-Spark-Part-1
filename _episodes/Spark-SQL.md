---
title: "Spark SQL"
time: 0

objectives:
- "Introduction to Spark SQL"
---

- A new module in Apache Spark that integrates relational processing with Spark’s functional programming API.
- Offers much tighter integration between relational and procedural in processing
- Includes a highly extensible optimizer, Catalyst, that makes it easy to add data sources, optimization rules, and data types.

Goals for Spark SQL
- Support relational processing both within Spark programs and external data sources using a programmer-friendly API.
- Provide high performance using established DBMS techniques.
- Easily support new data sources, including semi-structured data and external databases amenable to query federation.
- Enable extension with advanced analytics algorithms such as graph processing and machine learning.

- What are DataFrames?

DataFrames are a recent addition to Spark (early 2015).

The DataFrames API:

- is intended to enable wider audiences beyond “Big  Data” engineers to leverage the power of distributed  processing
- is inspired by data frames in R and Python (Pandas)
- designed from the ground-up to support modern big  data and data science applications
- an extension to the existing RDD API

See databricks.com/blog/2015/02/17/introducing-dataframes-in-spark-for-large-scale-data-science.html

<img width="428" alt="Screen Shot 2022-04-05 at 11 40 09 AM" src="https://user-images.githubusercontent.com/47697537/161826718-c9947abf-92f6-47b1-b495-6d0c1fc3644a.png">

<img width="416" alt="Screen Shot 2022-04-05 at 11 40 32 AM" src="https://user-images.githubusercontent.com/47697537/161826767-a38bc817-a73f-4a5b-8bd1-63bc0a90d859.png">




