# API registro y modificación de alumnos 📝

_Este es un proyecto personal, realizado en PHP con el framework FLIGHT, sirve para añadir, solicitar o eliminar alumnos de la base de datos, con los metodos: GET, POST, DELETE Y PUT._


# Requerimientos ✍️
- PHP => 8.2.0
- Composer => 2.5.4
- Servidor APACHE

# Instalación 🚀
- Lo primero es clonar este repositorio en tu directorio escogido, ej: (xampp/htdocs).
- Acceder al fichero `index.php` y añadir tu base de datos en la linea 6.
- Acceder mediante terminal al directorio y ejecutar el comando `composer install` (esto instalará todas las dependencias necesarias).
- Iniciamos el servidor APACHE.

# Uso 👍

Estos son los endpoint disponibles para peticiones:

- GET/alumnos: //Solicita la informacion completa de la base de datos.
- POST/alumnos: //Crea un nuevo registro a tu base de datos.
- DELETE/alumnos: //Elimina un registro en especifico, debes añadir el `id: ` correspondiente para el borrado.
- PUT/alumnos: //Modifica un registro en especifico, debes añadir el `id: ` correspondiente para la modificación.
- GET/alumnos/`id`: //Solicita para lectura un registro en especifico, solo debes dejar claro en la ruta cual es el `id`.


# Autora 🖌️

Angeles Viña 
https://github.com/angeles-vs
