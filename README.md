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

## 4.- Diseño de Metodos
### 4.1 Metodo GET
|No.|Propiedad|Detalle|
|--|--|--|
|1|description|Endpoint raiz de la api|
|2|summary|Endpoint raiz|
|3|method|GET|
|4|endpoint|http://localhost:8000/|
|5|query param|NA|
|6|path param|NA|
|7|data|NA|
|8|version|v1|
|9|status code|200(ok)|
|10|response type|application/json|
|11|response|{"version":"v1,"message":"Endpoin raiz","datetime":"21/9/23 10:15"]|
|12|curl|curl -X GET 'http://locathost:8000/' -H 'acceptapplication/json'|
|13|status code(error)|NA|
|14|response type(error)|NA|
|15|response|NA|

### 4.2 Metodo GET a contactos
|No.|Propiedad|Detalle|
|--|--|--|
|1|description|Obtener informacion de la tabla contactos|
|2|summary|Obtener contactos|
|3|method|GET|
|4|endpoint|http://localhost:8000/contactos/|
|5|query param|NA|
|6|path param|NA|
|7|data|NA|
|8|version|v1|
|9|status code|200(ok)|
|10|response type|application/json|
|11|response|{"version":"v1,"message":"Endpoin raiz","datetime":"21/9/23 10:15"]|
|12|curl|curl -X GET 'http://locathost:8000/' -H 'acceptapplication/json'|
|13|status code(error)|NA|
|14|response type(error)|NA|
|15|response|NA|

### 4.3 Metodo POST
|No.1|Propiedad|Detalle|
|--|--|--|
|1|description||
|2|summary||
|3|method||
|4|endpoint||
|5|query param||
|6|path param||
|7|data||
|8|version||
|9|status code||
|10|response type||
|11|response||
|12|curl||
|13|status code(error)||
|14|response type(error)||
|15|response||

### 4.4 Metodo DELETE
|No.1|Propiedad|Detalle|
|--|--|--|
|1|description||
|2|summary||
|3|method||
|4|endpoint||
|5|query param||
|6|path param||
|7|data||
|8|version||
|9|status code||
|10|response type||
|11|response||
|12|curl||
|13|status code(error)||
|14|response type(error)||
|15|response||

### 4.5 Metodo PUT
|No.1|Propiedad|Detalle|
|--|--|--|
|1|description||
|2|summary||
|3|method||
|4|endpoint||
|5|query param||
|6|path param||
|7|data||
|8|version||
|9|status code||
|10|response type||
|11|response||
|12|curl||
|13|status code(error)||
|14|response type(error)||
|15|response||
