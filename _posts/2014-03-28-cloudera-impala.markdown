---
layout: post
title: "Impala"
author: Charlie Greenbacker
categories: data-mining
tags: Impala
---
Announced by Cloudera in October 2012, Impala is a Massively Parallel Processing (MPP) query engine implemented on Hadoop. It enables users to leave their data in HDFS or HBase and run your ad hoc queries or interactive reports without having to migrate the data into another special BI data warehouse.

[<img style="float: right" src="{{ site.url }}/img/impala-logo.png" />](http://impala.io/)

__Creator:__ [Cloudera](http://www.cloudera.com/)

__License:__ [Apache License 2.0](http://opensource.org/licenses/Apache-2.0)

__Website:__ [impala.io](http://impala.io/)

__Source:__ [github.com/cloudera/impala](https://github.com/cloudera/impala)

__Features:__

* Low latency, high concurrency SQL & BI queries
* Same interfaces as Apache Hive, but ~24x faster
* Written in C++; does not use MapReduce
