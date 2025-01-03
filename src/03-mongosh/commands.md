## Connect to container

```sh
docker-compose exec mongo bash
```

## Connect witch mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "rl de conexion"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```

