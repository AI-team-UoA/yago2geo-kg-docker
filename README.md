# YAGO2geo Knowledge Graph Docker

Docker to deploy the complete YAGO2geo (including YAGO2) knowledge graph, using Graphdb.

## Setup

To build the docker image run:

      docker build -t yago2geo .

To run the docker container image run:

      sudo docker run --name yago2geo-graphdb-container -p 7200:7200 yago2geo

A GraphDB instance will be online on http://localhost:7200
