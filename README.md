# Elasticsearch with django 



## How to install postgres using docker

```
$ docker run --name elastic-postgres -e POSTGRES_PASSWORD=elastic -e POSTGRES_DB=elastic -e POSTGRES_USER=elastic -d postgres

```

## How to install Elasticsearch using docker 

```
$ docker run -d --name elasticsearch --net somenetwork -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:tag

```
