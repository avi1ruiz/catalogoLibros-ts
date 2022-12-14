## Catalogo de libros

El proposito es crear un proyecto listo para subirse a producción, aprender fundamentos de base de datos y ORM's, bases de backend, y una utilidad para practicar frameworks backend

Se utiliza en el proyecto:
- TypeScript
- Express
- MySQL, Sequelize
- Handlebars
- JsonWebToken, Passport

Se puede acceder al proyecto con el siguiente enlace https://catalogolibros-ts-production.up.railway.app/api


---
### To-Do
- [x] Instalar dependencias, configurar la base de datos
- [x] Crear operaciones basicas del backend(CRUD)
- [x] Proteger las rutas del 'gestor de contenido' con JWT
- [x] Diseñar las rutas de usuarios
- [x] Rediseñar la inferfaz del gestor
- [x] Mejorar la estructura del codigo, agregar comentarios, refactorizar codigo para evitar repeticiones
- [x] Agregar variables de entorno
- [x] Desplegar
---
#### Dia 1 (31 de octubre)
- Hice la configuración inicial del proyecto
- Se creo una base para la utilización de express
- utilizando Sequelize como ORM se crearon las tablas en MySQL

#### Dia 2 (01 de noviembre)
- Configure el motor de plantillas
- Hubo cambios en los paquetes usados en desarrollo
- Agrege algunas rutas basicas en el panel
- Se diseñaron las peticiones para agregar un libro y categoria a la base de datos
- Se agrego ruta para consumir api, solamente admite peticiones GET

#### Dia 3 (02 de noviembre)
- Agregue metodo post provisional para eliminar elementos, debo agregar paquete "method-override"
- Agregar estilo a la vista principal del cms
- Cambios en los layouts
- Agrego barra de navegación del 'cms'
- Se agrego method-override, peticiones delete listas

#### Dia 4 (04 de noviembre)
- Agregue un dos rutas asociadas a la edición de un elemento 
- Junto a lo anterior, se agrego el formulario con ese proposito

#### Dia 5 (05 de noviembre)
- Se agregaron paquetes relacionados al sistema de sesiones
- Se creo la tabla asociada a los usuarios
- Se creo metodo post para registro
- Implemente la estrategia local para inicio de sesión
- Añadio la estragia con jwt para proteger rutas del gestor
- Se rediseño la pagina principal del gestor

#### Dia 6 (06 de noviembre)
- Se reestructuro parte del codigo para modularizarlo mas
- Se cambio el nombre de variables usando camelCase y en ingles
- Se empezo agregar variables de entorno
- Se agregaron todas las variables de entorno necesarias
- Se añadio script para despliegue
- Cambios menores en rutas de api
- Cambios en la vista principal

#### Dia 7 (14 de noviembre)
Nota. Ausente por cuestiones personales
- Se termino el rediseño de la página, a fin de que fuera mas agradable a la vista
- Se agrego una vista para el código de estado 404
- Se realizo el despliegue de la aplicación