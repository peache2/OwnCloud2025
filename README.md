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



