# MySQL with Docker (Windows 10)

## Install 

```bash
    docker-compose up

    # run in background
    docker-compsoe up -d

    docker ps
```

## Create Database

```bash
    docker exec -it mysql_container bash -l

    mysql -u root -p
```