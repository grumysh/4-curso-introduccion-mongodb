# Connect to container
```sh
docker-compose exec mongodb bash
```

# Connect with mongosh
```sh
mongosh "mongodb://root:root123@localhost:27018/?authMechanism=DEFAULT&tls=false"
```

# Show DBs or collections
```sh
show dbs
show collections
```