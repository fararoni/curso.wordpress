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

|Bases de datos| Usuario |Password
|--|--|--|
|alpha| alpha| alpha#2024|
| beta | beta |beta#2024|



### 3. Configurar instancias de wordpress


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2MTc0NTIzMDMsLTU1MzM0ODY2MCw0ND
MxNzIxLC0zNjg3MTgzMTIsMTIyNjQ2NTQxMSwtNjY1Mjg0NDI1
LDE4MTg1OTAyMjFdfQ==
-->