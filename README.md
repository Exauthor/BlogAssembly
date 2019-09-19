# To start

`git clone --recurse-submodules git@github.com:Warinyourself/BlogAssembly.git` </br>

`docker-compose up` </br>

## Resolve problem with header

`git branch save HEAD`

`git `

## Update all submodules

`git submodule foreach git pull origin master` </br>

## Start docker container

`docker ps` </br>

`docker exec -ti CONTAINER_ID bash` </br>

## Delete volume from mongo container

`docker-compose rm -fsv mongo` </br>

## Import to database

`mongorestore /docker-entrypoint-initdb.d/` </br>

## Export database from mongo

`mongodump --db admin -o /docker-entrypoint-initdb.d/` </br>
