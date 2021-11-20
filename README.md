# CONDE-DOCKU21
Página web para poder hacer reservas de mesas en la intranet de un restaurante.

## Comenzando 🚀
```
Para tener este proyecto en local, hacemos un git clone https://github.com/DaveOC45/PR1def.git
### IMPORTANTE crear el archivo config.php dentro de services y que contenga (con los datos de vuestro host de base de datos):

```
 define("SERVIDOR","localhost");
 define("USUARIO","root");
 define("PASSWORD","");
 define("BD","bd_restaurant");
```


Para acceder:
Hay dos tipos de usuarios:
- David, Arnau, Ivan (inicial en mayúsculas) --> Camareros
- Danny (inicial en mayúsculas) --> Mantenimiento
Contraseñas:
- David: qweQWE123
- Arnau: asdASD123
- Ivan: zxcZXC123
- Danny: admin123
```
## Pre-requisitos 📋
```
Tener instalado xampp con la base de datos metida, el 
sql está en este mismo repositorio en la carpeta bd.
```
## Instalación 🔧
```
Para meter la base de datos nos vamos a phpmyadmin y ahí 
en el apartado importar le damos a importar nuestra base de datos
que sería el fihceor sql-> bd_restaurant.sql

Una vez hecho eso y habiendo hecho el apartado de "comezando" ya lo tendríamos listo para empezar a meter en el hosting
```

## Ejecutando las pruebas ⚙️
```
Podemos hacer una prueba con el login, metemos uno de los usuarios con su contraseña(apartado comenzando) y si entramos al
apartado home significará que la conexión y la integración de la base de datos funcionan correctamente.
```
