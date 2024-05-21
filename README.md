# LMSGI EXAMEN UNIDAD 6 - 20/05/2024

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


## **PARTE A - FICHEROS XML EN JAVA - 2 puntos**

### Ejercicio 1 - 2 puntos
Descarga el archivo tiempo.xml que se encuentra dentro de este repositorio y añádelo a tu proyecto. Ahora vamos a procesar este fichero mediante un programa en Java. El programa deberá mostrar por pantalla la fecha del día que lluvió (precipitación > 0).

### Ejercicio 2 - 2 puntos
Crea un programa en Java que automáticamente escriba un fichero xml y lo guarde como archivo externo. Este se compondrá de un elemento raíz llamado persona. Dentro de persona encontramos elementos que son nombre, apellidos, fecha de nacimiento y correo electrónico. Rellénalo con tus datos. Ejecuta el programa de tal forma que el archivo resultante se guarde en la carpeta del proyecto.

## **PARTE B - CONSULTAS XPATH - 2 puntos**
### Ejercicio 3 - 2,4 puntos
Realiza las siguientes consultas en XPath sobre el documento xml del Ejercicio 1 (tiempo.xml). Para ello crea un documento (Google Docs) e incluye captura de su funcionamiento en BaseX (debe aparecer tanto la consulta como el resultado de dicha consulta). - 0,30 Cada consulta
a) Seleccionar todas las fechas de los reportes climáticos
b) Seleccionar la máxima temperatura máxima
c) Seleccionar la mínima temperatura mínima
d) Seleccionar los días con precipitaciones mayores a 10 mm
e) Seleccionar las velocidades del viento cuya unidad es km/h
f) Seleccionar los días con viento proveniente del Noroeste
g) Selecciona la temperatura máxima del 2024-05-21
h) Seleccionar las direcciones del viento de los días con descripción "Lluvioso"

## **PARTE C - CONSULTAS XQUERY - 2 puntos**
### Ejercicio 4 - 3,6 puntos
Realiza las siguientes consultas en XPath sobre el documento xml hospital.xml. Para ello crea continua con el  documento (Google Docs) e incluye captura de su funcionamiento en BaseX (debe aparecer tanto la consulta como el resultado de dicha consulta). - 0,60 Cada consulta
a) Obtener el nombre y diagnóstico de los pacientes que han sido diagnosticados con "Gripe"
b) Seleccionar el nombre y el diagnóstico del paciente con mayor edad.
c) Listar los nombres de los pacientes asignados a "Dra. María López", ordenados por edad ascendente
d) Obtener los nombres de los pacientes mayores de 30 años
e) Crea una tabla HTML con el nombre de cada médico y su especialidad mediante una consulta XQuery
f) Crea un documento HTML básico con estilos mínimos de CSS que incluya un listado de los pacientes y muestren sus diversos datos


