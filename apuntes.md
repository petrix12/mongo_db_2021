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

### Video 02. Antes de seguir avanzando
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
1. Modelos de base de datos NoSQL:
    + Clave valor.
    + Orientado a documentos.
    + Basado en columnas.
2. Commit Video 17:
    + $ git add .
    + $ git commit -m "Commit 017: Modelo de base de datos NoSQL"
    + $ git push -u origin main

### Video 18. Documentos
1. Ejemplo Script MongoDB:
    ```
    {
        _id: Object("6454558778854520"),
        Name: "Fernando",
        Year: 2002,
        Status: "Gb"
    }
    ```
    + Estructura:
    ```
    {
        Campo_1: Valor1,
        Campo_2: Valor2,
        ≡
        Campo_n: Valorn,
    }
    ```
2. Commit Video 18:
    + $ git add .
    + $ git commit -m "Commit 018: Documentos"
    + $ git push -u origin main

### Video 19. Colecciones
+ **Contenido**: principalmente indicar que las colecciones son un conjunto de documentos.
+ **Nota**: si queremos hacer una analogía con bases de datos SQL, las colecciones equivalen a las tablas y los documentos a filas.
1. Commit Video 19:
    + $ git add .
    + $ git commit -m "Commit 019: Colecciones"
    + $ git push -u origin main

### Video 20. Variables parte 1
1. Tipos de variables:
    + Nulo (null)
    + Booleana (true, false)
    + Enteras (números enteros)
    + Decimales (números reales)
    + Cadena de texto
    + Fecha
    + Expresiones regulares
2. Commit Video 20:
    + $ git add .
    + $ git commit -m "Commit 020: Variables parte 1"
    + $ git push -u origin main

### Video 21. Variables parte 2
1. Otros tipos de variables:
    + Arrays
    + Documentos embebidos
    + Identificadores de objetos
    + Datos binarios
    + Código JavaScript
2. Commit Video 21:
    + $ git add .
    + $ git commit -m "Commit 021: Variables parte 2"
    + $ git push -u origin main

## Sección 05: Aprendiendo a manejar MongoDB

### Video 22. Aprendiendo a utilizar MongoDB
1. Agregar MongoDB a las variables de entorno del sistemas:
    + Buscar en Windows 10 **Editar las variables de entorno del sistema** para desplegar el cuadro de diálogo **Propiedades del sistema**.
    + En la pestaña de **Opciones avanzadas** dar clic en **Variables de entorno...**.
    + En el cuadro de diálogo **Varibles de entorno** seleccionar **Path** del grupo **Varibles de usuario para bazop** y dar clic en **Editar...**.
    + En el cuadro de diálogo **Editar varible de entorno** dar clic en **Nuevo** y anexar la siguiente dirección:
        + C:\Program Files\MongoDB\Server\5.0\bin
    + Aceptar todos los cambios.
2. Iniciar el servidor de MongoDB ejecutando en cualquier terminal:
    + $ mongod
3. Iniciar la base de datos MongoDB:
    + $ mongo
4. En la terminal de MongoDB puedo ejecutar operaciones básicas como:
    + > 5 + 7
5. En la terminal de MongoDB puedo ejecutar código de JavaScript como:
    + > a =7
    + > b = 3
    + > a + b
6. Para ver las bases de datos:
    + > show dbs
7. Crear un documento:
    + > datos = { Nombre: "Abelardo", Edad: 47, Fecha: new Date() }
8. Crear base de datos **principio** o situarse en ella en caso de que exista.
    + > use principio
    + **Nota**: esta base de datos comenzará a existir realmente hasta que se le añada una colección.
9. Para saber en que base de datos estamos ubicados:
    > db
10. Crear colección **registros** en la base de datos actual (**principio**) con el documento **datos** que creamos anteriormente:
    + > db.registros.insert(datos)
    + **Nota**: con esta acción ya se ha creado la base de datos **principio** y la colección **registros**.
11. Para ver el documento **datos**:
    + > db.registros.find()
12. Para salir de MongoDB:
    + > exit
13. Commit Video 22:
    + $ git add .
    + $ git commit -m "Commit 022: Aprendiendo a utilizar MongoDB"
    + $ git push -u origin main

### Video 23. Aprendiendo a utilizar la Shell de MongoDB
1. Levantar servidor de MongoDB:
    + $ mongod
2. Ejecutar consola de MongoDB:
    + $ mongo
3. Salir de MongoDB:
    + > exit
4. Commit Video 23:
    + $ git add .
    + $ git commit -m "Commit 023: Aprendiendo a utilizar la Shell de MongoDB"
    + $ git push -u origin main

### Video 24. Creando la base de datos en MongoDB
1. Levantar servidor de MongoDB:
    + $ mongod
2. Ejecutar consola de MongoDB:
    + $ mongo
3. Crear base de datos **base** o situarse en ella en caso de que exista.
    + > use base
    + **Nota**: esta base de datos comenzará a existir realmente hasta que se le añada una colección.
4. Crear colección **estudiantes** en la base de datos actual (**base**):
    + > db.estudiantes.insert({ Nombre: "Juan", Edad: 30, Estado: "casado", "fecha_registro": new Date() })
    + **Nota**: con esta acción ya se ha creado la base de datos **principio** y la colección **registros**.
5. Para ver los documentos de la colección **estudiantes**:
    + > db.estudiantes.find()
6. Salir de MongoDB:
    + > exit
7. Commit Video 24:
    + $ git add .
    + $ git commit -m "Commit 024: Creando la base de datos en MongoDB"
    + $ git push -u origin main

## Sección 06: Aprendiendo a insertar datos

### Video 25. Insertando datos con insert
1. Levantar servidor de MongoDB:
    + $ mongod
2. Ejecutar consola de MongoDB:
    + $ mongo
3. Ubicarse en la base de datos **principio**:
    + > use principio 
4. Crear nuevo documento:
    + > db.registros.insert({ Nombre: "Fernando", Edad: 15, Estado: "Soltero", Cargo: "Empleado", "fecha_Ingreso": new Date() })
5. Para ver los documentos de la colección **registros**:
    + > db.getCollection('registros').find({})
6. Ejecutar: **Robo 3T.exe** y conectar con la base de datos **localhost** para navegar por las distintas colecciones y documentos.
7. Salir de MongoDB:
    + > exit
8.  Commit Video 25:
    + $ git add .
    + $ git commit -m "Commit 025: Insertando datos con insert"
    + $ git push -u origin main

### Tarea 01: Ejercicio insert
1. Tarea 1:
    + Realizar o crear una base de datos la cual tenga diferentes datos:
        - Nombre
        - Genero
        - Edad
        - fecha
    + Solción:
        + $ mongod
        + $ mongo (en otra terminal)
        + > use bd1
        + > db.datos.insert({ Nombre: "Pedro", Genero: "M", Edad: 49, fecha: new Date() })
        + > db.datos.insert({ Nombre: "Cesar", Genero: "M", Edad: 51, fecha: new Date() })
        + > db.datos.insert({ Nombre: "Ignacio", Genero: "M", Edad: 46, fecha: new Date() })
        + > db.datos.insert({ Nombre: "María", Genero: "F", Edad: 52, fecha: new Date() })
        + > db.datos.insert({ Nombre: "Abelardo", Genero: "M", Edad: 47, fecha: new Date() })
    + Para ver los documentos de forma más ordenada:
        + > db.getCollection('datos').find({}).pretty()
        + > exit

### Video 26. Insertando datos con insert en robo 3T
1. Levantar servidor de MongoDB:
    + $ mongod
2. Ejecutar consola de MongoDB:
    + $ mongo
3. Ejecutar: **Robo 3T.exe** y conectar con la base de datos **localhost**.
4. Seleccionar base de datos **principio** y dar clic en **Open Shell** del menú emergente.
5. Ejecutar la siguiente línea de códigp:
    + db.robo.insertOne({Ingreso: "insert_one", Fecha_Ingreso: new Date()})
6. Salir de MongoDB:
    + > exit
7.  Commit Video 26:
    + $ git add .
    + $ git commit -m "Commit 026: Insertando datos con insert en robo 3T"
    + $ git push -u origin main

### Video 27. Insertando datos con insert One
1. Levantar servidor de MongoDB:
    + $ mongod
2. Ejecutar consola de MongoDB:
    + $ mongo
3. Ir a la base de datos **principio**:
    + use principio
4. Crear nuevo documento con **insertOne**:
    + > db.registros.insertOne({ Nombre: "Peter", Edad: 18, Estado: "Soltero", Cargo: "Gerente", Dui: 12345678, "Fecha_Ingreso": new Date() })
5. Salir de MongoDB:
    + > exit
6.  Commit Video 27:
    + $ git add .
    + $ git commit -m "Commit 027: Insertando datos con insert One"
    + $ git push -u origin main

### Tarea 02: Ejercicio con InserOne
1. Levantar servidor de MongoDB:
    + $ mongod
2. Ejecutar consola de MongoDB:
    + $ mongo
3. Ir a la base de datos **principio**:
    + use tarea02
4. Anexar documentos a la colección **sitios**:
    + db.sitios.insertOne({sitio: "Soluciones++", visitas: 33, compartidos: 12, created_at: new Date()})
    + db.sitios.insertOne({sitio: "Herramientas Office", visitas: 37, compartidos: 3, created_at: new Date()})
    + db.sitios.insertOne({sitio: "Google", visitas: 733, compartidos: 512, created_at: new Date()})
    + db.sitios.insertOne({sitio: "Amazon", visitas: 933, compartidos: 712, created_at: new Date()})
    + db.sitios.insertOne({sitio: "Azure", visitas: 433, compartidos: 212, created_at: new Date()})
5.  Commit Tarea 02:
    + $ git add .
    + $ git commit -m "Commit Tarea 02: Ejercicio con InserOne"
    + $ git push -u origin main

### Video 28. Insertando datos con insert One en robo 3T
+ **Contenido**: insertar registros con **insertOne** en **Robo 3T**.
1.  Commit Video 28:
    + $ git add .
    + $ git commit -m "Commit 028: Insertando datos con insert One en robo 3T"
    + $ git push -u origin main

### Video 29. Insertando Datos con insert Many
+ **Contenido**: insertar registros con **insertMany** en **Robo 3T**.
1.  Commit Video 29:
    + $ git add .
    + $ git commit -m "Commit 029: Insertando Datos con insert Many"
    + $ git push -u origin main

### Video 30. Arreglos


0.35 - x
1 - 93



    ≡
    ```json
    ```

## Comandos Git:
+ Historial de commit:
    + git log --pretty=oneline
+ Borrar ultimo commit:
    + git reset HEAD^ --soft
+ Forzar push
    + git push origin -f

## MongoDB
+ Para iniciar el servidor de MongoDB:
    + Ejecutar **C:\Program Files\MongoDB\Server\5.0\bin\mongod.exe** en una terminal de Windows:
        + $ mongod