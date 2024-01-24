Introduction
============

The Comment Recommendation Framework is a modular approach to support scientists in the development of prototypes for
comment recommendation systems that can be used in real-world scenarios. The advantage of such a system is that it
relieves the scientist from the majority of the technical code and only prototype-specific components have to be developed. In this way, the researchers can invest
more time in the development of recommendation models and less time has to be spent in the development of a prototype.

It provides the researcher with different modules which cover every aspect of a comment recommendation system.
First, we have the system itself with a simple user-interface in form of a chrome extension and a Django API with a
recommendation model interface and Neo4J database. If researchers want to test a new model, they only have to implement
the model and the prototype can be used right away.

Additionally, we present a news agency scraper module to extract articles and comments from different news agencies or if the researchers have a dataset they want to use, we provide a
module to import the data into the Neo4J database.

This way, researchers can focus more on the development of their recommendations models, instead of spending time
developing a prototype from scratch.