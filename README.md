# Proyecto de Microservicios con Spring Boot, MySQL y Docker Compose

Este proyecto es una arquitectura de microservicios desarrollada en **Spring Boot**, donde la finalidad es demostrar cómo crear, comunicar y desplegar múltiples servicios de forma eficiente.
utilizamos
 **MySQL** como base de datos 
 **Docker Compose** para la orquestación de contenedores.

Tecnologías principales

- **Spring Boot** – Para crear servicios REST independientes y escalables.
- **MySQL** – Base de datos relacional para almacenamiento de datos.
- **Docker & Docker Compose** – Para contenerizar y levantar el entorno completo de forma automática.

**Microservicios utilizados**
**Api gateway** : Cumple un rol fundamental en la arquitectura moderna basada en 
microservicios pues su función principal es actuar como punto de entrada único para 
todas las peticiones externas hacia un conjunto de servicios internos 

intercomunicación entre : **Microservicio asignaturas** ; **Microservicio estudiantes**, **Microservicio usuarios**
ambas con bases de datos en MySQL  

**Microservicio eureka**: Servidor de registro encargado principalmente de permitir que los 
microservicios se encuentren y se comuniquen entre sí sin necesidad de conocer sus 
direcciones IP fijas. 

**Microservicio config**: Aplicacion y almacenamiento de propiedades para todos los 
microservicios.

