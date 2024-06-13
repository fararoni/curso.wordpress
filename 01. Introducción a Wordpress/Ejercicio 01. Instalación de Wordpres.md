# Ejercicio 01. Instalación de Wordpress
En el curso se van a usar tres instancias de wordpress:
1. alpha
2. beta
3. prod

## Recursos para descargar

### 1. Wordpress.
https://es-mx.wordpress.org/download/

La versión al día de hoy es 6.5.4
![Wordpress](https://i.imgur.com/G4dho4A.png)


### 2. Xampp

![Xampp](https://i.imgur.com/WMtuJ0j.png)

## Instalacion de xampp
1. Ejecutar el programa de instalación
2. Aceptar el Warning, e instalar xampp en c;\xampp
![warning](https://i.imgur.com/LzHqiFh.png)

![Instalador](https://i.imgur.com/WEKE39y.png)
3. Desactivar las siguientes casillas: 
	- FileZilla FTP Server
	 - Tomcat
	 - Perl
	 - Webalizer
![Opciones de instalación](https://i.imgur.com/5DjAwxn.png)

4. Iniciar la instalación.
5. Levantar los servicios Apache y MySQL

![](https://i.imgur.com/T81p0JV.png)


## Instalar instancias de wordpress
### 1. Wordpress
1.- Descomprimir el archivo instalador de wordpress `wordpress-6.5.4-es_MX.zip`en la carpeta `c:\xampp\htdocs` esto va a generar la carpeta `c:\xampp\htdocs\wordpress`.
![](https://i.imgur.com/QWa4YBx.png)

*La instalación tarda varios minutos*

![Descomprimir wordpress](https://i.imgur.com/k3Hirrp.png)

2. Renombre la carpeta para que quede con el siguiente nombre : `c:\xampp\htdocs\alpha`

3. Hacer una copia de la carpeta alpha y renombrarla con el nombre `beta`

![](https://i.imgur.com/0F79OQm.png)

![](https://i.imgur.com/rb04bBq.png)


### 2. Crear dos bases de datos en mysql

1. Ingresar a phpMyAdmin para crear las dos bases de datos:
![](https://i.imgur.com/T8GQTt8.png)


2. Crear las dos bases de datos:

|Bases de datos| Usuario |Password
|--|--|--|
|alpha| alpha| alpha#2024|
| beta | beta |beta#2024|


**1. Seleccionar la opción de "Cuentas de usuarios".** y a contiinuación " **Agregar cuenta de usuario**"
- Nombre de host: local
- Crear base de datos con el mismo nombre y otorgar todos los privilegios.: seleccionado
- Privilegios globales Seleccionar todo

![](https://i.imgur.com/lTtg0Qz.png)


### 3. Configurar instancias de wordpress

#### 3.1 Instancia ALPHA
**Configuración de la base de datos**
1. Ingresar a http://localhost/alpha
![](https://i.imgur.com/b2LADon.png)

2. Agregar los datos que solicita

- Nombre de la base de datos: **alpha**
- Usar la base de datos: **alpha** 
- Cambiar el prefijo de la tabla: **wpalpha_**

![](https://i.imgur.com/QY6mV1k.png)
![](https://i.imgur.com/7gxXxdV.png)

<!--stackedit_data:
eyJoaXN0b3J5IjpbODI2MDI0LDYxMTYyMzQ1MSwtNjI3NjI3ND
c0LC01NTMzNDg2NjAsNDQzMTcyMSwtMzY4NzE4MzEyLDEyMjY0
NjU0MTEsLTY2NTI4NDQyNSwxODE4NTkwMjIxXX0=
-->