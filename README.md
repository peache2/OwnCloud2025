# OwnCloud2025
![OC](OwnCloud.png)
En este tutorial explicativo voy a enseñar como podemos descargar OwnCloud de manera rapida en *Ubuntu 24.04* y conceptos basicos (usuarios, archivos, etc...)

## Instalación de apache2, mysql y php

### 1-Actualizamos nuestra maquina usando los 2 siguientes comandos
![cmd](1.png)
![cmd](2.png)

### 2-Instalamos el servidor web `apache2`
![cmd](3.png)

### 3-Instalamos el servidor de base de datos `mysql-server`
![cmd](4.png)

### 4-Vamos a instalar la libreria de `php`, ya que este es el lenguaje que sali
![cmd](5.png)
![cmd](6.png)

### 5-Despues de esto reiniciaremos el servidor `apache2`
![cmd](7.png)

## Configurando MySQL

### 1-Accedemos dentro de la consola de MySQL `sudo mysql` 
![cmd](8.png)

### 2-Creamos la base de datos MySQL llamada `bbdd`
![cmd](9.png)

### 3-Creando el usuario. Vamos a crear una IP personalizada para que podamos acceder, en este caso la vamos a llamar `localhost`
![cmd](10.png)

### 4- Vamos a asignarle todos los privilegios a nuestro usuario
![cmd](11.png)

### 5- Salimos de la base de datos
![cmd](12.png)

### 6- Comprobamos que todo funcion correctamente 
![cmd](13.png)
![cmd](14.png)

## Descarga del ficher de OwnCloud
https://download.nextcloud.com/server/releases/latest.zip
![cmd](15.png)

### 1-Copiaremos el archivo descargado a la carpeta `/var/www/html`
![cmd](16.png)

### 2-Nos dirijimos al directorio `/var/www/html`
![cmd](17.png)

### 3-Descomprimimos el archivo descargado
![cmd](18.png)

### 4-Copiamos los archivos de la carpeta /var/www/html al nombre de la carpeta de los archivos
![cmd](19.png)


### 5-Eliminamos el archivo index.html de apache2
![cmd](21.png)

### 6-Aplicamos todos los permisos a la aplicación web
![cmd](22.png)
![cmd](23.png)
![cmd](24.png)

## Instalación de PHP 7.4

Instalamos ¡todos los requisitos de PPA:
![cmd](27.png)

Instalamos todo lo necesario para poder trabajar con PPA.
![cmd](28.png)


Actualitzamos los repositorios:
![cmd](29.png)


Vamos a instalar todas las librerias de `PHP` de la versión 7.4
![cmd](30.png)

![cmd](31.png)

![cmd](32.png)

Vamos a selecionar la version de `PHP` que necesitamos, en este caso la *7.4*
![cmd](33.png)


Activamos todos los modulos de `apache2` que estrictamente necesitamos
![cmd](34.png)


![cmd](35.png)


Reiniciamos `apache2`
![cmd](36.png)



## Vamos a nuestro navegador de confianza y buscamos http://localhost

* **usuari:** usuario
* **contrasenya:** password
* **base de dades:** bbdd
* **domini:** localhost
