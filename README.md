# To start

`git clone --recurse-submodules git@github.com:Warinyourself/BlogAssembly.git` </br>
`docker-compose up` </br>

# Export database from mongo

`mongodump --db admin -o /docker-entrypoint-initdb.d/` </br>

# To database

`mongorestore /docker-entrypoint-initdb.d/` </br>
