# Proyecto Ingeniería de Software II.
## Enunciado del proyecto.
## Herramientas a utilizar
### Backend
* [Node](https://nodejs.org/en/)
* [Express](http://expressjs.com/)
* [Repositorio](https://github.com/Angatupyry/backendis2)
#### Frontend
* [VueJS](https://vuejs.org/)
* [Repositorio](https://github.com/acem0301/frontis2)
# Link el proyecto.
[Getión de Proyecto](https://gestionproyecto.netlify.com/)
## Usuario para login. 
crolon 
123


# Entregables
## Entrega_01: 08/03 Login + Dashboard inicial
### Distribución de tareas. 
* Arturo Arias - Rodrigo Gómez; diseño del DER y creación del script para la base de datos.
* Adriana Estigarribia; inicialización del proyecto frontend y avances. 
* César Rolón; inicialización del proyecto backend y avances. 

## Entrega_02: 15/03 Módulo Administración (Crear Roles, Crear Usuarios, Asignar Roles a Usuarios)
## Distribución de tareas.
* César Rolón : backend, conexión con la base de datos. 
* Adriana Estigarribia : frontend, vistas, componentes.
* Rodrigo Gómez : Creación de interfaz de rol en el issue crearRol. 

# Versión 15/03 
El sistema ya se conecta con la base de datos pero tenemos que lograr levantar postgres en un servidor free para que no se tenga que configrar la base de datos y correr el script en cada máquina que incia el proyecto. Por tanto, para esta entrega se usan datos en duro de usuarios. El frontend ya consume la API.


## Entrega_03: 22/03 Módulo Desarrollo (Crear Proyecto, Crear Tareas, sin Conectar todavía)
## Distribución de tareas.
* César Rolón : backend, frontned. Conexión de base de datos.  
* Adriana Estigarribia : backend, frontend, vistas, componentes. 
* Rodrigo Gómez : backend. Listar Proyectos 
* Arturo Arias: Gestión de configuración de datos en el servidor Heroku y Netilify

# Versión 22/03 
Estamos utilizando servidores de free en donde configurarmos la base de datos postgres. 
El servidor nos permite crear 10 mil rows en la versión free. 
El link del proyecto se encuentra al inicio.
Faltan renderizar las vistas una vez que se crean proyectos e ítems. Es decir, no actualiza automáticamente, hay que ir hasta otra ruta y volver a acceder a la ruta anterior para ver los nuevos datos. Detalles que corregiremos en la próxima entrega. 
Consideramos que no se puede eliminar un proyecto. Queremos inactivar una vez que finalicen todas las fases automáticamente (en un futuro). Ídem para ítem. 

