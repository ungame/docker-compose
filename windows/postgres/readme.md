# PostgreSQL com Docker

```bash
    # subindo o postgres em background
    docker-compose up -d

    # acessando o console do postgres
    docker exec -it postgres_container bash

    # login no postgres
    psql --host=database --username=root --dbname=mydb

    # listar tabelas
    \dt

    # detalhes da tabela
    \d+ nome_da_tabela

    # mudar de banco de dados
    \c postgres

    # criando novo banco de dados
    create database dbname

    \c dbname
```

## Como resetar o banco de dados

```bash
    docker volume rm postgres_postgres_data
```
