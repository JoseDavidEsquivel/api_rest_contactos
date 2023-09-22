# Desing Document: API REST CONTACTOS

## 1.- Descripcion
Ejemplo de una API REST para gestionar contactos en una DB utilizando FastAPI

## 2.- Objetivo
Utiilzar un eemplo de siseño de una API REST de tipo CRUD y su posterior codificacion utilizando el framework [FastAPI](https://fastapi.tiangolo.com)

## 3.- Diseño de la BD
Para este ejemplo se utilizara el gestpr de bases de datos [SQLite3](https://www.sqlite.org/index.html) con la siguiente tabla:

### 3.1 Tabla: contactos
|No.|Campo|Tipo|Restricciones|Descripcion|
|--|--|--|--|--|
|1|id_contactos|int|PRIMARY KEY|llave primaria de la tabla|
|2|nombre|varchat(150)|not null|nombre|
|3|primer_apellido|varchar(50)|not null  |  |
|4|segundo_apellido|varchar(50)|not null  |  |
|5|email|varchar(50)|not null |  |
|6|telefoo|varchar(15)|not null  |  |
