# Glossary #

https://docs.mongodb.com/manual/reference/glossary/

## BSON ##
TODO

## Collection ##
TODO (https://docs.mongodb.com/manual/reference/glossary/#term-collection)

## CRUD ##
Create, Read, Update, and Delete operations

## disaster recovery ##
TODO

## document ##
MongoDB documents are similar to JSON objects. The values of fields may include other documents, arrays, and arrays of documents.

    {
      name: "sue",
      age: 26,
      status: "A",
      groups: [ "news", "sports" ]
    }

## horizontal scaling ##
TODO

## JSON ##
TODO

## fault tolerance ##
TODO

## performance ##
TODO

## record ##
A record in MongoDB is a [document](GLOSSARY.md#document), which is a data structure composed of field and value pairs.

## replica set ##
A replica set is a group of MongoDB servers that maintain the same data set, providing redundancy and increasing data availability.
See [replication](GLOSSARY.md#replication) for more details.

## replication ##
TODO

## replication facility ##
Same as [replica set](GLOSSARY.md#replica-set)

## shard key ##
The field MongoDB uses to distribute documents among members of a sharded cluster.
* [shard key](https://docs.mongodb.com/manual/reference/glossary/#term-shard-key)
* [sharded cluster](https://docs.mongodb.com/manual/reference/glossary/#term-sharded-cluster)
* [Shard Keys](https://docs.mongodb.com/manual/core/sharding-shard-key/#shard-key)
