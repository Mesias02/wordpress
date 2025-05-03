## 1. Título
Implementación de Contenedores en Docker para Hospedar un Sitio WordPress

## 2. Tiempo de duración
Tiempo estimado: 120 minutos

## 3. Fundamentos
Docker permite la ejecución de aplicaciones en contenedores, proporcionando un entorno independiente que simplifica la administración de software. En este caso, se crearán los contenedores necesarios para un sitio WordPress, incluyendo una base de datos MySQL y una herramienta de gestión phpMyAdmin, sin necesidad de configuraciones adicionales dentro de los contenedores.

El objetivo es desplegar los contenedores de manera eficiente, asegurando que cada uno de ellos esté correctamente interconectado dentro de una red de Docker para permitir la comunicación entre servicios. Según Docker Inc. (n.d.), la modularidad y eficiencia de los contenedores facilitan el despliegue de aplicaciones sin interferencias en el sistema anfitrión.

## 4. Conocimientos previos
Para completar esta práctica, el estudiante debe tener conocimientos en:

Comandos básicos de Docker, como creación y gestión de contenedores (Red Hat, 2023).

Conceptos de redes en Docker, para garantizar la comunicación entre contenedores (Turnbull, 2014).

Persistencia de datos en Docker, mediante volúmenes.

## 5. Objetivos a alcanzar
Crear y ejecutar los contenedores de WordPress, MySQL y phpMyAdmin en Docker.

Implementar una red para la comunicación entre los contenedores.

Utilizar volúmenes para almacenamiento persistente.

## 6. Equipo necesario
Computador con sistema operativo Windows/Linux/Mac.

Instalación de Docker (versión XXXX).

Acceso a Docker Hub para obtener imágenes oficiales.

## 7. Material de apoyo
Documentación oficial de Docker.

Guía de la asignatura.

Cheat sheet de comandos en Linux.

## 8. Procedimiento
Paso 1: Crear una red para la comunicación entre contenedores
![image](https://github.com/user-attachments/assets/1cc970bf-01cf-4f27-a194-ffbc313acfcd)
---
validar red

![image](https://github.com/user-attachments/assets/4b15a4c9-4044-422e-b436-4ecf1bca7a6f)
---
Paso 2: Crear volúmenes para almacenamiento persistente
Volumen wordpress-data

![image](https://github.com/user-attachments/assets/7d0bbf41-c78f-4085-84d2-92a877cec74a)
---

Volumen mysql-data

![image](https://github.com/user-attachments/assets/dabe2344-6805-400c-9578-5ee10f734217)


Paso 3: Crear y ejecutar el contenedor de MySQL

Paso 4: Crear y ejecutar el contenedor de phpMyAdmin

Paso 5: Crear y ejecutar el contenedor de WordPress

Paso 6: Validar que los contenedores estén corriendo


9. Resultados esperados
Los contenedores deben estar correctamente creados y en ejecución.

La red debe permitir la comunicación entre WordPress, MySQL y phpMyAdmin.

Los datos deben permanecer almacenados en los volúmenes asignados.

10. Bibliografía
Docker Inc. (n.d.). Docker documentation. Recuperado de https://docs.docker.com/

Red Hat. (2023). Introducción a la gestión de contenedores. Recuperado de https://www.redhat.com/es/topics/containers

Turnbull, J. (2014). The Docker Book: Containerization is the new virtualization. James Turnbull.
