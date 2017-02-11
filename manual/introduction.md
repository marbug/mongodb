# Introduction #
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

MongoDB provides high performance data persistence. In particular:

* Support for embedded data models reduces I/O activity on database system.
* Indexes support faster queries and can include keys from embedded documents and arrays.

### Rich Query Language ###

MongoDB supports a rich query language to support [read and write operations (CRUD)](CRUD.md) as well as:

* [Data Aggregation](data-aggregation.md)
* [Text Search](text-search.md)
* [Geospatial Queries](geospatial-queries.md)

### High Availability ###

MongoDB's [replication facility](replication.md), called [replica set](replication.md), provides:

* automatic failover
* data redundancy.

A [replica set](replication.md) is a group of MongoDB servers that maintain the same data set, providing redundancy and increasing data availability.

### Horizontal Scalability ###

MongoDB provides horizontal scalability as part of its core functionality:

* [Sharding](sharding.md) distributes data across a cluster of machines.
* MongoDB 3.4 supports creating [zones](zone-sharding.md) of data based on the shard key. In a balanced cluster, MongoDB directs reads and writes covered by a zone only to those shards inside the zone. See the [Zones manual page](zone-sharding.md) for more information.

### Support for Multiple Storage Engines ###

MongoDB supports multiple [storage engines](storage-engines.md), such as:

* [WiredTiger Storage Engine](storage-engines/wiredtiger.md)
* [MMAPv1 Storage Engine](storage-engines/mmapv1.md)

In addition, MongoDB provides pluggable storage engine API that allows third parties to develop storage engines for MongoDB.

[prev page: MongoDB manual](../MANUAL.md) | [next page: Databases and Collections](databases-and-collections.md)
