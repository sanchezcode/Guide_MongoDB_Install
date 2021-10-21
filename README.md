# Guide_MongoDB

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





