# Polyglot-Persistent-System
The term polyglot persistence simply means that when storing data, it is best to use multiple storage technologies, chosen, based upon the way data is being used by individual applications or components of a single application. Different kinds of data are best dealt with different data stores. The core objective of this project is to implement an e-commerce database system that can efficiently deal with the deluge of data coming in several types. An e-commerce application epitomizes the need for various kinds of data stores i.e. Polystores. Major hurdles are encountered by them in areas of scalability and availability. Relational databases are better for transactions and ACID guarantees but they fall short in providing linear scalability for large volumes of data. Schema less NoSQL stores are better when scalability is a requirement. Through this project, we propose a hybrid data store architecture using a polyglot data mapper for an e-commerce application intending to achieve better querying performance than a standalone DBMS under the hood.

## How to run
There are three models in this project: one that uses only SQLite, one that uses only MongoDB, and another that uses SQLite, MongoDb, and Redis. All the models are created using Jupyter notebook, and hence each individual file has a step-by-step (one cell after another) execution process. Run the files in the order as follows:

### Only SQLite model
1. Run Full_fledge_SQLite (Configure the database connection details and the path to the data files)
2. Run SQLite_all_alone

### Only MongoDB model
1. Run Full_fledge_MongoDb (Configure the database connection details and the path to the data files)
2. Run MongoDB_all_alone

### Polyglot model
1. Run SQLite_MongoDB_Redis (Configure the database connection details and the path to the data files)
2. Run integration_latest

## Additional read (you might find it intriguing)
- https://www.infoq.com/articles/polyglot-persistence-microservices
- https://www.infoq.com/presentations/microservices-polyglot-persistence
- https://www.meetup.com/Silicon-Valley-NoSQL/events/247519984/
- https://medium.com/netflix-techblog/netflixs-viewing-data-how-we-know-where-you-are-in-house-of-cards-608dd61077da
