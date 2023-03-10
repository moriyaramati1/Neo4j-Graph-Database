# Neo4j Graph Database
In this project, I presented data from the "Friends" series by Neo4j. 
The graph shows relationships and types of relationships between nodes.

## Features:
* Docker Platform
* REST API
* Graph DB

## Folder Structure & Explanation of files
There are 2 types of nodes:
- Apartment Number
- Person 

For creating the Nodes and Relationships i used py2neo package.

Friends_data.csv - contains the data about friends' characters.
friends.py - contains the flask app and functions for building the graph.
DokerFile - for creating the container for the application.
docker-compose- for creating the database container and app container and interacting between them.
templates folder - for HTML files of each query.