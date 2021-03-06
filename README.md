# Guide_MongoDB_Install

Contenido:

- INSTALACIÓN DE MONGODB Y COMPASS EN WINDOWS (10 y 11)
- INSTALACIÓN DE MONGODB Y COMPASS EN LINUX (UBUNTU 20.04.4 LTS y 22.04 LTS)

______________________________________________

**** INSTALACIÓN DE MONGODB Y COMPASS EN WINDOWS (10 y 11) ****
______________________________________________

1 - Vamos a su pagina oficial https://www.mongodb.com/try/download/community

2 - Descargamos la version que nos recomienda para nuestro sistema operativo que sale por defecto

![image](https://user-images.githubusercontent.com/54609399/137845052-a1a0c6ec-913f-4b28-89f0-3cac27a843d2.png)

3 - Ahora ejecutamos el instalador

![image](https://user-images.githubusercontent.com/54609399/137845417-7035457d-da80-496a-9742-e2ffb1d926a0.png)

4 - Damos next

![image](https://user-images.githubusercontent.com/54609399/137845457-42240368-b54d-4186-97e1-20acd9248fe7.png)

5 - Aceptamos los terminos y damos next

![image](https://user-images.githubusercontent.com/54609399/137845509-01f72fd5-581b-473f-bde7-f911292bbac6.png)

6 - Damos complete

![image](https://user-images.githubusercontent.com/54609399/137845546-06837b3c-c625-40f0-bd99-645c489069eb.png)

7 - no damos ninguna opcion y damos next, porque esto es para generar contraseñas a las BD y si se nos olvida alguna esto generara conflictos como estara intaladas en nuestro pc por eso no necesitamos ponerles clave por eso dejamos por defecto y damos next.

![image](https://user-images.githubusercontent.com/54609399/137845609-4e451695-4360-41e3-830f-2aa80b024654.png)

8 - dejamos checkeado compass que es la parte grafica de MongoDB y damos next

![image](https://user-images.githubusercontent.com/54609399/137845670-e1a7f7ad-5fb0-4e46-8492-fade8320426c.png)

9 - damos install 

![image](https://user-images.githubusercontent.com/54609399/137845694-901ef5f6-7ca7-4274-84cf-7c4f92401149.png)

Esperamos que termine el proceso

![image](https://user-images.githubusercontent.com/54609399/137845897-a7bd25f5-0bc1-4672-9c4b-373d3640bb0d.png)


10 - si sale esto nos toca darle en close se debe cerrar todo lo que no deje instalar  (esto es porque tienen abierto algo que para mongo impide la ejecución)

![image](https://user-images.githubusercontent.com/54609399/137845784-2ef244ea-60c0-4f63-a8ee-46624f3b6a0b.png)

Continuamos el proceso y nos pide reiniciar asi que reiniciamos la maquina

![image](https://user-images.githubusercontent.com/54609399/137845861-e3187bae-7383-47c4-8c98-7720d68f5a79.png)


11 - Podemos continuar con la instalacion

![image](https://user-images.githubusercontent.com/54609399/137845821-58c5010b-7008-49ba-91ac-64f1ac484da1.png)

NOTA: NOS PUEDES PEDIR REINICIO DEL SISTEMA REINICIAMOS Y AL VOLVER CONTINUAMOS CON LO SIGUIENTE

Una vez finalizado procedera abrir compass

![image](https://user-images.githubusercontent.com/54609399/137846155-7d13a039-8b77-482d-bf7c-28440d638b84.png)

cerramos esos mensajes guias dandole la X a la ventanita secundaria de WELCOME TO MONGODB

![image](https://user-images.githubusercontent.com/54609399/137846195-8282fcec-c1f9-4e33-8779-a3ec531c13ee.png)

Dejamos todas checkeadas y damos start

![image](https://user-images.githubusercontent.com/54609399/137846255-cdebdd6f-a2b0-4654-8e75-e04b00041fd6.png)

ya nos queda listo el mongo compass

![image](https://user-images.githubusercontent.com/54609399/137846355-6ce7c86a-0040-451b-b70d-0ab8d3de246c.png)

12 - En el disco local C creamos una carpeta data (EN MINUSCULA TODA) aqui es donde mongo va guardar las bases de datos, los de linux y mac no deben crear esta carpeta

![image](https://user-images.githubusercontent.com/54609399/137846709-45d0ff77-6e79-4898-8532-46b530ac7703.png)

14 - Dentro de data creamos una carpeta db (EN MINUSCULA Y DEBE SER DB NUNCA BD ) los d elinux y mac tampoco deben crear esta carpeta

![image](https://user-images.githubusercontent.com/54609399/137846792-4020f9cf-2855-46cc-b51a-046da36ca212.png)


15 - vamos a la variable de entorno para que nuestro windows reconozca mongoDB y lo pueda ejecutar en su consola de comandos, los de linux y mac no necesitan este paso

para ello vamos al buscador y escribimos variables de entorno y seleccionamos la siguiente opcion

Editar variables de entorno del sistema

![image](https://user-images.githubusercontent.com/54609399/137847159-868dd2aa-9e84-4d30-84e6-81a4efaf4c57.png)

damos clck en variables de entorno

![image](https://user-images.githubusercontent.com/54609399/137847209-77e0cd77-2dd3-44bd-bcd5-4bc429ade917.png)

damos click en el path del segundo cuadrito y damos en el boton editar

![image](https://user-images.githubusercontent.com/54609399/137847496-37d63466-69d6-461f-9e4d-ef36fceed559.png)

nos abre esta ventanita pero todabia no vamos hacer nada aqui

![image](https://user-images.githubusercontent.com/54609399/138189503-a06114bc-d13f-4ac0-9fa3-6ef769d4a678.png)

vamos a ir a buscar una ruta , en el disco C buscamos donde quedo instalado mongo y entramos hasta la carpeta bin y copiamos la ruta en la barra de arriba

![image](https://user-images.githubusercontent.com/54609399/137847588-0b1c9e96-dbed-4f44-a7be-212fb47adf32.png)

Volvemos a la ventanita donde no hicimos nada y damos al boton nuevo y ponemos la nueva ruta y damos aceptar

![image](https://user-images.githubusercontent.com/54609399/137847646-e8ab4d3e-a4b1-4020-91d0-8c32b1d9c395.png)

Luego nos lleva a esta ventanita de nuevo y damos aceptar

![image](https://user-images.githubusercontent.com/54609399/137847675-ae5bccb7-0b1c-4340-8426-79494980296d.png)

nos devuelve a esta ventana y le damos en aceptar tambien

![image](https://user-images.githubusercontent.com/54609399/137847706-fe97f411-8d29-4f4b-bfad-c915886ba9d3.png)

Volvemos a la carpetica donde esta instalado mongo y vamos a la carpeta bin


y ejecutamos el archivo mongod (demonio de mongo) esto ejecuta el servidor de mongo (los de linux y mac abren una consola y ejecutan la palabra mongod y ya se ejecuta el servidor no tiene consola propia de mongo)

![image](https://user-images.githubusercontent.com/54609399/137847911-27250942-6ffc-404f-b2c2-864db5f8308b.png)


luego de que tenemos el servidor ejecutando abrimos la consola mongo que es el cliente donde podemos trabajar (los de linux y mac tienen que abrir otra consola a aprte y escribir mongo ejecutarlo y ya tienen el cliente tampoco tienen consola propoa de mongo)

![image](https://user-images.githubusercontent.com/54609399/137848011-0bc0d307-84fb-454f-94b8-b72a62c49f26.png)

con esto ya tenemos instalado mongo en el equipo tambien podemos comporbar la version de mongo abriendo otra consola del sistema
y colocando mongo --version

![image](https://user-images.githubusercontent.com/54609399/137848080-ede1ca18-684c-42d5-9339-3ceb0347dc39.png)

______________________________________________

**** INSTALACIÓN DE MONGODB Y COMPASS EN LINUX (UBUNTU 20.04.4 LTS y 22.04 LTS) ****
______________________________________________

1 - Entramos a la pagina guía de instalación de MongoDB:

https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-ubuntu/

2 - Nos ubicamos en la sección de linux Ubuntu

![image](https://user-images.githubusercontent.com/54609399/164111442-da9ba0c8-fa7c-4e42-872f-f672c8b939bc.png)

3 - Podemos seguir toda la documentación, pero aqui te hare un resumen para ahorrar tiempo.

Iniciamos con el primer comando

```
sudo wget -qO - https://www.mongodb.org/static/pgp/server-5.0.asc | sudo apt-key add -
```

![image](https://user-images.githubusercontent.com/54609399/167243871-ec2eddca-7de6-4261-9bbd-d0838ffae117.png)

Al ejecutar el comando recibiremos un OK

![image](https://user-images.githubusercontent.com/54609399/167243910-3a0a3437-b286-4a7f-b040-2c601ef9fe67.png)

4 - Ejecutamos los siguientes comandos:

```
sudo apt-get install gnupg
```
```
sudo wget -qO - https://www.mongodb.org/static/pgp/server-5.0.asc | sudo apt-key add -
```

![image](https://user-images.githubusercontent.com/54609399/167243970-6efb6ccf-0339-44b5-8d61-6a9a842f6238.png)

5 - Realizamos el siguiente comando y luego hacemos un update para recargar todos los paquetes de MongoDb instalados hasta el momento

```
sudo echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/5.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-5.0.list
```
```
sudo apt-get update
```

![image](https://user-images.githubusercontent.com/54609399/167244111-d6cbf72b-1d8a-4699-af4d-4d27b4a0cb40.png)

6 - Ahora vamos a instalar la ultima versión actual de MongoDB

```
sudo apt-get install -y mongodb-org
```
![image](https://user-images.githubusercontent.com/54609399/167244187-549f1b6f-05af-409d-af9a-eaf7801748f5.png)

Al terminar ejecutamos la siguiente combinación de comandos y damos ENTER:

```
echo "mongodb-org hold" | sudo dpkg --set-selections
echo "mongodb-org-database hold" | sudo dpkg --set-selections
echo "mongodb-org-server hold" | sudo dpkg --set-selections
echo "mongodb-org-shell hold" | sudo dpkg --set-selections
echo "mongodb-org-mongos hold" | sudo dpkg --set-selections
echo "mongodb-org-tools hold" | sudo dpkg --set-selections
```

![image](https://user-images.githubusercontent.com/54609399/167244238-8c8223eb-3247-4f08-a0d7-2c398402279d.png)

7 - Instalamos el medio por el que se ejecutara mongo en Linux llamado systemd

```
sudo ps --no-headers -o comm 1
```

![image](https://user-images.githubusercontent.com/54609399/167244274-30a224a6-a042-4d30-91dc-d8b1e3a38088.png)

8 - Con este comando inicializamos el servidor de mongo en Linux

```
sudo systemctl start mongod
```
Si todo sale bien veremos lo siguiente al dar ENTER

![image](https://user-images.githubusercontent.com/54609399/167244321-66085fbe-74b5-4d19-815c-58ccdc1e94a2.png)

NOTA: En caso que salga error al iniciar podemos ejecutar el siguiente comando para reiniciar el systemd (que ejecuta el servidor de Mongo)

```
sudo systemctl daemon-reload
```

9 - Para verificar que el servidor esta activo realizamos el siguiente comando

```
sudo systemctl status mongod
```
Podemos ver que el servidor de MongoDB se esta ejecutando en nuestro sistema

![image](https://user-images.githubusercontent.com/54609399/167244478-582c354c-49db-4922-bba1-b446a951e768.png)

NOTA: Para reiniciar el servidor tenemos cualquiera de estos dos comandos:

```
sudo systemctl enable mongod
```
o (recomendado)
```
sudo systemctl restart mongod
```

10 - Cuando necesitemos detener el servidor usamos el siguiente comando:

```
sudo systemctl stop mongod
```

y verificamos con

```
sudo systemctl status mongod
```

![image](https://user-images.githubusercontent.com/54609399/167244967-4b7397a6-2d7f-401c-a0ce-a5431fb23ca4.png)

11 - Para el siguiente paso necesitamos que el servidor este activo para probar Mongo Compass al instalarlo y el cliente por consola de MongoDB (Estos son los comandos que se seguiran utilizando de ahora en adelante cada que necesitemos usar MongoDB)

```
sudo systemctl start mongod
```
```
sudo systemctl status mongod
```

![image](https://user-images.githubusercontent.com/54609399/167245068-8cba2149-f3ad-4df6-9a6d-8464cfed862e.png)


12 - Para ejecutar el cliente de MongoDB el servidor debe estar activo y en una nueva pestaña o en la misma ejecutamos el siguiente comando:

```
mongo
```

![image](https://user-images.githubusercontent.com/54609399/167245244-1eb93e30-d9e4-4e94-ae12-cb43b739b703.png)

13 - Aqui podemos probar y ejecutar codigo de MongoDB para manipular nuestras bases de datos.

![image](https://user-images.githubusercontent.com/54609399/167245308-73c33fb7-0999-4560-86b1-b9557ae86544.png)

Ejemplo: Ver las bases de datos actuales

```
show dbs
```

![image](https://user-images.githubusercontent.com/54609399/167245369-b5e2f3ef-dde5-4082-8ac1-c7a838db8f20.png)

14 - Iniciaremos con la instalacion de Mongo Compass el cual nos permitira ver y trabajar con nuestras bases de datos con una interfaz grafica.

Ingresamos a la pagina de descarga de Mongo Compass

https://www.mongodb.com/try/download/compass

Automaticamente nos ubicara en la version mas estable y .deb (no cambiar ninguna de estas opciones)

![image](https://user-images.githubusercontent.com/54609399/167245489-42700c74-e3f8-4092-a8e8-4e9be90495cb.png)

15 - Una vez descargado ejecutamos el instalador

![image](https://user-images.githubusercontent.com/54609399/167245574-3f233b1f-d83d-4a9e-b150-68f1263180f1.png)

16 - Instalamos el Mongo Compass

![image](https://user-images.githubusercontent.com/54609399/167245611-0be57626-15dd-4d3f-951c-b3a8312f860e.png)

Verificamos que quedo instalado cuando veamos lo siguiente:

![image](https://user-images.githubusercontent.com/54609399/167245632-47766534-a741-495c-b293-baa056e160bb.png)

17 - Vamos a buscar la aplicacion de Mongo Compass en nuestro inicio

![image](https://user-images.githubusercontent.com/54609399/167245682-6962b128-7ed4-490b-8755-ecfc6bb0d6e3.png)

![image](https://user-images.githubusercontent.com/54609399/167245714-391872d8-f82a-4361-876b-dabd71ead490.png)

18 - Abrimos la aplicación y realizamos los siguientes pasos iniciales:

Damos Next hasta el final

![image](https://user-images.githubusercontent.com/54609399/167245762-f018e0c2-caf5-45eb-bac0-17162c4111f0.png)

Presionamos el boton Get Started

![image](https://user-images.githubusercontent.com/54609399/167245798-66fb6b59-e03e-4709-a9e5-66b8f48f3153.png)

Dejamos todos los checks seleccionados y damos en Start Using Compass

![image](https://user-images.githubusercontent.com/54609399/167245819-06642247-d5c8-44c5-ac28-de33f065cb60.png)

Estamos listos para iniciar con Mongo Compass

![image](https://user-images.githubusercontent.com/54609399/167245853-5a4127d5-01db-4a99-9387-06af85507d89.png)

Al dar en Connect podemos ver las bases de datos iniciales

![image](https://user-images.githubusercontent.com/54609399/167245873-a1aad96e-a73f-4af8-9ed9-9327b5926514.png)

Recordemos que para que Mongo Compass funcione debe estar ejecutandose el servidor de MongoDB

![image](https://user-images.githubusercontent.com/54609399/167245911-b5dab0e3-25df-4f1a-92ad-167174721225.png)

Y con todos estos pasos completados ya podemos iniciar a trabajar con estas herramientas.





