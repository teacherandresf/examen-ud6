# LMSGI EXAMEN RECUPERACIÓN UNIDAD 6 - 29/05/2024

## Indicaciones generales
Lee atentamente estas indicaciones generales antes de realizar esta prueba:
* Crea una carpeta que se llame TUSINICIALES_EX_UD_6.
* Dentro de dicha carpeta inicializa un proyecto en java utilizando Maven o cualquier otra forma que conozcas para poder correr Java.
* Dentro de la carpeta principal o main, donde se encuentra el Apop.java, vas a incluir los archivos que se te pidan, ya sea xml o .java.
* Debes subir a la tarea de classroom dicha carpeta como .zip: Click derecho en la carpeta, Click en "Enviar a", Click en "Carpeta comprimida (en zip)".
* Realiza cada apartado siguiendo las indicaciones al pie de la letra.
* Puedes acceder a los apuntes, diapositivas, ejercicios resueltos, internet y consultar cualquier cosa <b>exceptuando la IA</b>, que queda prohibida.
* Revisa el tiempo, la entrega se cierra 5 minutos antes de que termine la clase - 🕙 11:10.
* Acuérdate de ir guardando constantemente. En caso de no visualizarse algun archivo, dicho apartado o ejercicio contará como un 0 <b>no revisable. También si haces uso de la IA. </b>


## **PARTE A - FICHEROS XML EN JAVA**

### Ejercicio 1 - 2 puntos
Descarga el archivo videojuegos.xml que se encuentra dentro de este repositorio y añádelo a tu proyecto. Ahora vamos a procesar este fichero mediante un programa en Java. El programa deberá mostrar por pantalla los títulos de los juegos que tienen una calificación mayor a 8.

### Ejercicio 2 - 2 puntos
Crea un programa en Java que automáticamente escriba un fichero xml y lo guarde como archivo externo. Este se compondrá de un elemento raíz llamado persona. Dentro de persona encontramos elementos que son nombre, apellidos, fecha de nacimiento y correo electrónico. Rellénalo con tus datos. Ejecuta el programa de tal forma que el archivo resultante se guarde en la carpeta del proyecto.

## **PARTE B - CONSULTAS XPATH**
### Ejercicio 3 - 2,4 puntos
Realiza las siguientes consultas en XPath sobre el documento XML del Ejercicio 1 (videojuegos.xml). Para ello crea un documento (Google Docs) e incluye captura de su funcionamiento en BaseX (debe aparecer tanto la consulta como el resultado de dicha consulta). - 0.30 Cada consulta

a) Seleccionar todos los títulos de los videojuegos
b) Seleccionar la calificación más alta
c) Seleccionar la fecha de lanzamiento más temprana
d) Seleccionar los videojuegos con calificación mayor a 8
e) Seleccionar las plataformas de los videojuegos
f) Seleccionar los videojuegos lanzados en 2020
g) Seleccionar la calificación del juego "Hades"
h) Seleccionar los títulos de los videojuegos con calificación menor a 8

## **PARTE C - CONSULTAS XQUERY**
### Ejercicio 4 - 3,6 puntos
Realiza las siguientes consultas en XQuery sobre el documento XML reservas_hotel.xml. Para ello crea continúa con el documento (Google Docs) e incluye captura de su funcionamiento en BaseX (debe aparecer tanto la consulta como el resultado de dicha consulta). - 0.60 Cada consulta

a) Obtener el nombre y la fecha de check-in de las reservas hechas para una habitación "Suite"
b) Seleccionar el nombre y la fecha de check-in de la reserva más reciente
c) Listar los nombres de los clientes asignados a la "Suite 101", ordenados por fecha de check-in ascendente
d) Obtener los nombres de los clientes con una estancia mayor a 5 días
e) Crear una tabla HTML con el nombre de cada cliente y su tipo de habitación mediante una consulta XQuery
f) Crear un documento HTML básico con estilos mínimos de CSS que incluya un listado de las reservas y muestren sus diversos datos.


