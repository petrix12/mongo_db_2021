# Curso Completo de Bases de datos MongoDB y NoSQL
+ [URL del curso en Udemy](https://www.udemy.com/course/curso-completo-de-bases-de-datos-mongodb-y-nosql)
+ [URL del repositorio en GitHub](https://github.com/petrix12/mongo_db_2021.git)

## Antes de iniciar:
1. Crear proyecto en la página de [GitHub](https://github.com) con el nombre: **mongo_db_2021**.
    + **Description**: Proyecto para seguir el curso de Bases de datos MongoDB y NoSQL, creado por Álvaro Chirou, Walter Coto y Kevin García en Udemy.
    + **Public**.
2. En la ubicación raíz del proyecto en la terminal de la máquina local:
    + $ git init
    + $ git add .
    + $ git commit -m "Commit 000: Antes de iniciar"
    + $ git branch -M main
    + $ git remote add origin https://github.com/petrix12/mongo_db_2021.git
    + $ git push -u origin main

## Sección 01: Introducción

### Video 01. Recomendaciones para una mejor experiencia en el curso
+ **Contenido**: recomendación de como seguir el curso.
1. Commit Video 01:
    + $ git add .
    + $ git commit -m "Commit 001: Recomendaciones para una mejor experiencia en el curso"
    + $ git push -u origin main

### Video 002. Antes de seguir avanzando
+ **Contenido**: funcionamiento del sistema de calificaciones de Udemy.
1. Commit Video 02:
    + $ git add .
    + $ git commit -m "Commit 02: Antes de seguir avanzando"
    + $ git push -u origin main

### Video 03. Sobre su Profesor. Álvaro Chirou
+ **Contenido**: presentación de Álvaro Chirou.
1. Commit Video 03:
    + $ git add .
    + $ git commit -m "Commit 003: Sobre su Profesor. Álvaro Chirou"
    + $ git push -u origin main

### Video 04. Sobre su Profesor. Walter Coto
+ **Contenido**: presentación de Walter Coto.
1. Commit Video 04:
    + $ git add .
    + $ git commit -m "Commit 004: Sobre su Profesor. Walter Coto"
    + $ git push -u origin main

### Video 05. Presentación de instructor Kevin García
+ **Contenido**: presentación de Kevin García.
1. Commit Video 05:
    + $ git add .
    + $ git commit -m "Commit 005: Sobre su Profesor. Walter Coto"
    + $ git push -u origin main

### Video 06. Modalidad de entrega de tareas
+ **Contenido**: forma en que se pueden colocar las tareas en la página del curso.
1. Commit Video 06:
    + $ git add .
    + $ git commit -m "Commit 006: Modalidad de entrega de tareas"
    + $ git push -u origin main

## Sección 02: Fundamentos de base de datos

### Video 07. ¿Qué es un administrador de base de datos?
+ **Contenido**: funciones de un daministrador de base de datos.
1. Commit Video 07:
    + $ git add .
    + $ git commit -m "Commit 007: ¿Qué es un administrador de base de datos?"
    + $ git push -u origin main

### Video 08. Tipos de base de datos
+ **Contenido**: tipos de bases de datos.
1. Commit Video 08:
    + $ git add .
    + $ git commit -m "Commit 008: Tipos de base de datos"
    + $ git push -u origin main

### Video 09. ¿Qué son los datos?
+ **Contenido**: explicación sobre los tipos de datos.
1. Commit Video 09:
    + $ git add .
    + $ git commit -m "Commit 009: ¿Qué son los datos?"
    + $ git push -u origin main

### Video 10. Sistemas gestores de base de datos
+ **Contenido**: presentación de algunos gestores de bases de datos.
1. Commit Video 10:
    + $ git add .
    + $ git commit -m "Commit 010: Sistemas gestores de base de datos"
    + $ git push -u origin main

### Video 11. Diferencias entre base de datos relacionales y no relacionales
+ **Contenido**: deferencias principales entre los tipos de bases de datos SQL y NoSQL.
1. Commit Video 11:
    + $ git add .
    + $ git commit -m "Commit 011: Sistemas gestores de base de datos"
    + $ git push -u origin main

## Sección 03: Instalando herramientas

### Video 12. Introdución
+ **Contenido**: indicaciones previas a la instalación de MongoDB.
1. Commit Video 12:
    + $ git add .
    + $ git commit -m "Commit 012: Introdución"
    + $ git push -u origin main

### Video 13. Instalando MongoDB
1. Ingresar a la página de descarga de MongoDB: https://www.mongodb.com/try/download/community
2. En **Descarga disponibles** seleccionar:
    + Versión: 5.03 (current)
    + Plataforma: Windows
    + Paquete: msi
3. Descargar y ejecutar como administrador:
    + **Next**.
    + Aceptar términos y **Next**.
    + Instalación personalizada y **Next**.
    + Dejar todo como esta y **Next**.
    + Deseleccionar **Install MongoDB as a Service** y **Next**.
    + Deseleccionar **Install MongoDB Compas** y **Next**.
    + Presionar **Install**.
    + Presionar **Finish**.
4. Commit Video 13:
    + $ git add .
    + $ git commit -m "Commit 013: Instalando MongoDB"
    + $ git push -u origin main

### Video 14. Iniciando Servicio MongoDB
1. Ubicación de instalación de MongoDB:
    + C:\Program Files\MongoDB\Server\5.0\bin\mongod.exe
2. Crear ruta para la ubicación de la base de datos:
    + C:\data\db
3. Ejecutar **mongod.exe** en una terminal de Windows.
    + $ mongod
    + **Nota**: cuando esta acción se ejecuta por primera vez se generan un conjunto de archivos y carpetas en **C:\data\db**. Estos datos no deben ser eliminados.
4. Ejecutar **mongo** en otra terminal de Windows para finalizar la iniciación del servicio de MongoDB.
    + $ mongo
5. Commit Video 14:
    + $ git add .
    + $ git commit -m "Commit 014: Iniciando Servicio MongoDB"
    + $ git push -u origin main

### Video 15. Instalando Robo 3T
1. Descargar Robo 3T en:
    + https://robomongo.org
2. Instaler Robo 3T:
    + **Siguiente**.
    + Aceptar términos en **Acepto**.
    + Dejar directorio destino y **Siguiente**.
    + Presionar **Instalar**.
    + Dejar marcada la casilla **Ejecutar Robo 3T 1.X** y presionar **Terminar**.
    + En el cuadro de diálogo **EULA** seleccionar **I agree** y dar clic en **Next**.
    + Dar clic en **Finish**.
    + En cuadro de diálogo **MongoDB Connections** dar clic en **Create**.
    + Nombrar la conexión **localhost** y dar clic en **Save** y luego en **Connect**.
        + **Nota**: para poder establecer conexión el servicio debe de estar iniciado.
3. Commit Video 15:
    + $ git add .
    + $ git commit -m "Commit 015: Instalando Robo 3T"
    + $ git push -u origin main

## Sección 04: Fundamentos básicos de MongoDB

### Video 16. Base de datos NoSQL
+ **Contenido**: acerca de bases de datos NoSQL.
1. Commit Video 16:
    + $ git add .
    + $ git commit -m "Commit 016: Base de datos NoSQL"
    + $ git push -u origin main


### Video 17. Modelo de base de datos NoSQL
### Video 18. Documentos
### Video 19. Colecciones
### Video 20. Variables parte 1
### Video 21. Variables parte 2




0.35 - x
1 - 93



    ≡
    ```json
    ```

## MongoDB
+ Para iniciar el servidor de MongoDB:
    + Ejecutar **C:\Program Files\MongoDB\Server\5.0\bin\mongod.exe** en una terminal de Windows:
        + $ mongod