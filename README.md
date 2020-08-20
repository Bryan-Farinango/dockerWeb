# DockerWeb Prueba Servicios sobre redes - ESFOT
Integrantes:  
* Bryan Farinango
* Josselyn Vela
## Desarrollo 🚀
*  Docker con Postgres
*  Dcoker con Mariadb
*  Consumo de datos con servidor apache 

## 1. Implementacion de Docker con Postgres 📌
Ejecutamos el siguiente comando
```
docker pull postgres
```
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/1.png)

A continuación corremos nuestra base de datos y contraseña en postgres
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/2.png)

Realizamos la conexión a postgres en nuestro archivo php
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/3.png)

Consumo de datos con Postgres
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/6.png)

## 2. Implementación de Docker con MariaDB 📌
Corremos nuestra base de datos con MariaDB y nuestra contaseña
```
docker run --name mariadb002 -e MYSQL_ROOT_PASSWORD=root -d mariadb:tag
```
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/4.png)

Realizamos la conexión a MariaDB en nuestro archivo php
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/5.png)

Consumo de datos con MariaDB
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/7.png)

## 3. Docker con apache y php 📌
Ejecutamos el comando para el pull con docker
```
docker pull php:7.4-apache
```
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/8.png)

Ejecutamos el comando de docker para el servicio 
```
docker build -t servicio
```
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/9.png)

Corremos nuestro archivo
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/10.png)

Consumo de datos de MariaDB usando apache
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/11.png)

Consumo de datos de Postgres usando apache
![](https://github.com/Bryan-Farinango/dockerWeb/blob/master/assets/12.png)
