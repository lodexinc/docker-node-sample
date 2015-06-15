Sample node.js & docker application
===

Install docker: [Docker](https://docs.docker.com/installation/)

Install docker-compose: [Docker Compose](https://docs.docker.com/compose/install/)


Build and run container:
--
```
cd ./src
docker build -t docker-node-sample .
docker run -p "9001:9000" -t docker-node-sample
```
