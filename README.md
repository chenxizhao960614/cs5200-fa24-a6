# CS 5200 Assignment 6: Replica Sets vs Sharding

This repository contains everything you need to complete the hands-on MongoDB assignment. 
Follow the instructions in the assignment to set up and experiment with **replica sets** and **sharded clusters**.

## Repository Structure

- `replica-set/`: Files needed to set up and test a MongoDB replica set.
- `sharded-cluster/`: Files needed to set up and test a MongoDB sharded cluster.

## Prerequisites

Make sure you have the following installed:

- Docker: https://docs.docker.com/get-docker/
- MongoDB CLI Tools: https://www.mongodb.com/try/download/database-tools
- Git: https://git-scm.com/downloads

## Quick Start

Clone this repository.

### Replica Set Setup

Navigate to the `replica-set/` folder and follow the assignment instructions.

```bash
cd replica-set
docker-compose up --wait
```

Stop the replica set and remove the containers before starting the sharded cluster.

```bash
docker-compose down
```

### Sharded Cluster Setup

Navigate to the `sharded-cluster/` folder and follow the assignment instructions.

```bash
cd sharded-cluster
docker-compose up --wait
```

Stop the sharded cluster and remove the containers when you're done.

```bash
docker-compose down
```

