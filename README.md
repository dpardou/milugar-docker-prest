# API para PostgreSQL

## ¿Cómo instalar la API de PostgreSQL? 

  - Modificar el archivo prest.toml con los datos de la base de datos PostgreSQL.

## ¿Cómo ejecutar la API de PostgreSQL?

Teniendo Docker instalado, ejecutar los siguientes comandos:

    docker build --rm -t docker-prest .
    docker create -d -p 8080:8080 --name docker-prest-server docker-prest
    docker start docker-prest-server

## ¿Cómo usar la API de PostgreSQL?

La documentación para crear una API de PostgreSQL está [aquí](https://postgres.rest).
