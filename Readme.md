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

## Nginx proxy manager
[Documentation](https://nginxproxymanager.com/setup/)

![manager2](https://user-images.githubusercontent.com/97110006/152161120-2aa7891a-f4c4-484c-b1cc-138ad5589fc4.png)

## Worflow
![workflow](https://user-images.githubusercontent.com/97110006/152161151-426febee-5369-439f-b6e8-e93a4d830fc1.png)
