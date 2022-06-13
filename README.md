# Examen-andreubonet

- Para realizar la prueba del examen he utilizado Play with docker-Labs.

# Apartado A

<p> El primer paso al abrir Play with docker-Labs será Logearnos con el nombre de usuario del docker hub y una contraseña que creemos nosortros.</p> 

![Captura-1](https://user-images.githubusercontent.com/91874398/173301147-00da62d9-d607-4eb7-b47f-c17352be933c.PNG)

## Ejemplo 1

<p> En el primer ejemplo, lo que haremos será descargar una imagen ubuntu:18.04, con el comando >docker pull ubuntu:18.04, haremos un >docker images para ver que se nos ha descargado correctamente la imagen. A continuación haremos un >docker run -it ubuntu:18.04 /bin/bash, la función de este comando será crear un contenedor, dandonos un acceso a un shell del mismo contenedor, accederemos al contenedor como root para salir del root ejecturamos el comando >exit.
</p>

![Captura-2](https://user-images.githubusercontent.com/91874398/173302162-b401749f-27b3-48c9-a2d6-a6c42ae487ba.PNG)

## Ejemplo 2

<p> En el ejemplo 2, crearemos un contenedor centOS:18.04 y listar el contenedor de la carpeta / con el comando >docker run centos ls /, este contenedor pasará a estar parado y como es habitual no podremos acceder a él. He lanzado la version centos, sin el 18:04 para que me coga la última versión
</p>

![Captura-3](https://user-images.githubusercontent.com/91874398/173304776-c2ef65c3-b5f7-4d83-b6fa-ee6f01d8969d.PNG)


## Ejemplo 3

<p> En este ejemplo, crearemos un contenedor httpd lanzando el comanod >docker run htppd, se nos creará un servidor Web Apache 2.4 en la ip mostrada y se nos muestra por pantalla el log de dicho servicio. 
</p>

![Captura-4](https://user-images.githubusercontent.com/91874398/173305144-b5cd5d0f-24a4-4a9c-a2c2-24d483571978.PNG)


## Ejemplo 4

<p> En el ultimo ejemplo crearemos un contenedero debian 9 y mostraremos el contenido de una carpeta con el comando -w. Al crear el contenedor se ejecuta la orden ls desde el directorio /etc, posteriormente el contenedor pasa a estar parado. Y ya no podremos acceder a él.
</p>

![Captura-5](https://user-images.githubusercontent.com/91874398/173306366-6e6b307d-9f1d-4fa2-8991-f936b1e35633.PNG)


## Seguimiento de Sistema

<p> Como último paso del apartado A, mostraremos un seguimento del sistema, lo primero mostraremos los contenedores en ejeccución con el comando >docker ps, y después mostraremos todos los contenedores que esten en ejeccución o ya esten parados con el comando >docker ps -a.
</p>


![Captura-6](https://user-images.githubusercontent.com/91874398/173306673-4a616caa-af30-41b6-b42c-4a28791a5b5e.PNG)


# Apartado B

![Captura-8](https://user-images.githubusercontent.com/91874398/173313502-eb661edd-2147-428b-b7f3-a5dd86b17e34.PNG)





