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

TODO
