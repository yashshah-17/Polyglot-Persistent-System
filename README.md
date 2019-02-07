# Polyglot-Persistent-System

Something new, something fun!

The term polyglot persistence simply means that when storing data, it is best to use multiple
storage technologies, chosen, based upon the way data is being used by individual applications or
components of a single application. Different kinds of data are best dealt with different data
stores. The core objective of this project is to implement an e-commerce database system that can
efficiently deal with the deluge of data coming in several types. An e-commerce application
epitomizes the need for various kinds of data stores i.e. Polystores. Major hurdles are
encountered by them in areas of scalability and availability. Relational databases are better for
transactions and ACID guarantees but they fall short in providing linear scalability for large
volumes of data. Schema less NoSQL stores are better when scalability is a requirement.
Through this project, we propose a hybrid data store architecture using a polyglot data mapper
for an e-commerce application intending to achieve better querying performance than a
standalone DBMS under the hood.

Additional read (you might find it intriguing):
https://www.infoq.com/articles/polyglot-persistence-microservices
https://www.infoq.com/presentations/microservices-polyglot-persistence
https://www.meetup.com/Silicon-Valley-NoSQL/events/247519984/
https://medium.com/netflix-techblog/netflixs-viewing-data-how-we-know-where-you-are-in-house-of-cards-608dd61077da
