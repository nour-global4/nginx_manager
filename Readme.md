## Setup

```
docker compose up -d

git clone [repo]

cd [repo]

docker compose up -d

docker exec -it [container] sh

composer install
```

## Connect to database

```
DB_CONNECTION=mysql
DB_HOST=host.docker.internal
DB_PORT=33087
DB_DATABASE=leads
DB_USERNAME=root
DB_PASSWORD=secret
```