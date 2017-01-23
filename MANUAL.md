# MongoDB manual #

Let's follow [MongoDB Manual](https://docs.mongodb.com/manual/) first and note main points starting from current file.

## Getting Started ##

MongoDB manual has version of 'Getting Started' for different languages (Python, Java, etc) and some of them differs not only by language code but also by structure and info. That's why IMHO it's better to compare them later... TODO :)

So, let's start from [manual's introduction](https://docs.mongodb.com/manual/introduction/)

## Introduction ##
MongoDB is an open-source document database that provides high performance, high availability, and automatic scaling.

## Document Database ##
A record in MongoDB is a document, which is a data structure composed of field and value pairs. MongoDB documents are similar to JSON objects. The values of fields may include other documents, arrays, and arrays of documents.

    {
      name: "sue",
      age: 26,
      status: "A",
      groups: [ "news", "sports" ]
    }

The advantages of using documents are:

* Documents (i.e. objects) correspond to native data types in many programming languages.
* Embedded documents and arrays reduce need for expensive joins.
* Dynamic schema supports fluent polymorphism.

## Key Features ##

### High Performance ###

MongoDB provides high performance data persistence. In particular,
* Support for embedded data models reduces I/O activity on database system.
* Indexes support faster queries and can include keys from embedded documents and arrays.

### Rich Query Language ###

MongoDB supports a rich query language to support [read and write operations (CRUD)](manual/CRUD.md) as well as:
* [Data Aggregation](manual/data-aggregation.md)
* [Text Search](manual/text-search.md)
* [Geospatial Queries](manual/geospatial-queries.md)

### High Availability ###

MongoDB’s [replication facility](manual/replication.md), called [replica set](manual/replication.md), provides:
* automatic failover
* data redundancy.

A [replica set](manual/replication.md) is a group of MongoDB servers that maintain the same data set, providing redundancy and increasing data availability.

TODO
