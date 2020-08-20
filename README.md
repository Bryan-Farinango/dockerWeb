# DockerWeb Prueba Servicios sobre redes - ESFOT
Integrantes:  
* Bryan Farinango
* Josselyn Vela
## Desarrollo 🚀
Descargamos la imagen con el comando «docker pull» y el nombre de la imagen a descargar
```
docker pull wordpress:4.7.2-apache
```
Creamos y ejecutamos un docker de nombre «wordpress01»
```
docker run --name wordpress01 -d wordpress:4.7.2-apache
```
Comprobamos que el contenedor se está ejecutando
```
docker ps
```
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/p1.png)

Podemos obtener el siguiente error a continuación y borraremos un docker duplicado para solucionarlo

![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/p2.png)

Configuración de base de datos MariaDB y corriendo el servidor WEB Wordpress


![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/p3.png)

Servidor web Wordpress

![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/p4.png)
































          
