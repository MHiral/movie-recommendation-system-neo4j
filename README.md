# movie-recommendation-system-neo4j


=== Setup

This is to access the Neo4j instance.

NEO4J_URI = neo4j+s://2a9865c8.databases.neo4j.io
NEO4J_USERNAME = neo4j
NEO4J_PASSWORD = VOQ_aOTU3FIC5NBslltZqfY3xCQvNkzH2jNwircWigk

Note: These credentials are added to the code section and can be run directly.


=== Graph-Based Recommendations
We'll take a look at how you can generate graph-based real-time personalized product recommendations using a dataset of movies and movie ratings, but these techniques can be applied to many different types of products or content.

****
Data sources:
* https://grouplens.org/datasets/movielens/[MovieLens]
****


=== The Property Graph Model

The data model of graph databases is called the labeled property graph model.

*Nodes*: The entities in the data.

*Labels*: Each node can have one or more *label* that specifies the type of the node.

*Relationships*: Connect two nodes. 
They have a single direction and type.

*Properties*: Key-value pair properties can be stored on both nodes and relationships.

=== Nodes

`Movie`, `Actor`, `Director`, `User`, `Genre` are the labels used in this example.

=== Relationships

`ACTED_IN`, `IN_GENRE`, `DIRECTED`, `RATED` are the relationships used in this example.

=== Properties

`title`, `name`, `year`, `rating` are some of the properties used in this example.


