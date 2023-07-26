# Evaluation of the tools

The code in here allows to me evaluate/test both tools (Budibase ad Retool) against one MySQL instance. This offers the flexibility of using the same dataset to create different types of apps using both tools.

## Instructions
Follow the order listed when starting up the components. These two docker networks created by retool is used by Budibase as well.

 - [ ] retool-onpremise-master_backend-network
       retool-onpremise-master_db-connector-network

$ cd retool-onpremise-master
$ docker-compose up
$ cd Budibase
$ docker-compose up
$ docker-compose ps -a      // To view the status of docker containers

## Ports

3000 - retool
5013 - phpMyAdmin
10000 - Budibase