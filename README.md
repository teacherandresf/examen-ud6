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
### Ejercicio 3 - 2 puntos
Realiza las siguientes consultas en XPath sobre el documento xml del Ejercicio 1 (tiempo.xml). Para ello crea un documento (Google Docs) e incluye captura de su funcionamiento en BaseX (debe aparecer tanto la consulta como el resultado de dicha consulta). 

## **PARTE C - CONSULTAS XQUERY - 2 puntos**
### Ejercicio 5 - 1,5 puntos
Realiza un XML Schema para el ejercicio 1 que valide el documento XML que has creado.

### Ejercicio 6 - 1,5 puntos
Realiza un XML Schema para el ejercicio 2 que valide el documento XML que has creado.

### Ejercicio 7 - 3 puntos
En este ejercicio, tu tarea es crear un esquema XML (XSD) que valide documentos XML que contienen información sobre un sistema de gestión de pacientes de un hospital. El esquema debe definir la estructura y las restricciones que deben cumplir los documentos XML para ser considerados válidos.

Instrucciones:

Define un elemento raíz llamado hospital que puede contener uno o más elementos paciente.
Cada elemento paciente debe contener elementos para el nombre, el apellido, la fecha de nacimiento, el sexo, el número de seguro social y una lista de consultas médicas del paciente.
Define un elemento consulta para representar una consulta médica. Cada consulta debe tener elementos para la fecha de la consulta, el médico que realizó la consulta, el motivo de la consulta y el diagnóstico.
Aplica las siguientes restricciones adicionales:
El nombre y el apellido del paciente no pueden estar vacíos.
La fecha de nacimiento del paciente debe estar en el formato "AAAA-MM-DD".
El sexo del paciente debe ser "Masculino" o "Femenino".
El número de seguro social del paciente debe ser una cadena de 9 dígitos.
La fecha de la consulta médica debe estar en el formato "AAAA-MM-DD".
El motivo de la consulta médica y el diagnóstico no pueden estar vacíos.

Define un elemento <hospitalizacion> para registrar las hospitalizaciones de los pacientes. Cada hospitalización debe tener elementos para la fecha de ingreso, la fecha de alta, la habitación asignada y el motivo de la hospitalización.
Aplica restricciones adicionales según lo consideres necesario para garantizar la validez de los documentos XML de las hospitalizaciones.
