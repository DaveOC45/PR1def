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
## Despliegue 📦
```
Para desplegar la página necesitaremos un Hosting, en mi caso utilizaré "000webhost". El primer paso es registrarnos en la
página oficial -> https://es.000webhost.com/ , seguidamente creamos la base de datos en el apartado "Database Manager" y 
una vez hecho ya podríamos subir todos nuestros ficheros y carpteas en el apartado de "File Manager", es muy importante 
subirlo dentro de htdocs sino no funcionará. La carpeta tmp que viene por defecto no se ha de eliminar ya que es aquí donde 
se guardan los ficheros temporales de sesiones y el fichero .htaccess que se encuentra dentro de la carpeta public_html 
tampoco se ha de eliminar. En el fichero config que hemos subido le cambiamos la configuración y le ponemos el usuario,
contraseña y nombre de la bd que le hemos puesto al crear la base de datos.

Una vez hecho todo lo anterior, la página nos debería aparecer en estado running. Para comprobar que todo ha funcionado 
nos vamos de vuelta a la página principal de 000webhost y damos clic en el enlace que se nos ha generado, clicamos y 
si podemos introducir el login es que ha funcionado todo correctamente. Aunque veamos que el login funciona no viene de 
más comprobar que todos los otros apartados de la página funcionen.
```
## Construido con 🛠️
```
-XAMPP
-000webhost
-PHP
-JS
-HTML
-CSS
```
## Contribuyendo 🖇️
Por favor lee el CONTRIBUTING.md para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖
Puedes encontrar mucho más de cómo utilizar este proyecto en nuestro GitHub.

## Versionado 📌
Usamos Git para el versionado



