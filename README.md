# UT08-IndexedDB

Dada la práctica de la unidad 7 del VideoSystem, implementa las siguientes funcionalidades en la misma.
 1. Utilizando el API Web Storage, permite que se caché la aplicación. Piensa detenidamente qué recursos deberán ser cacheados y cuáles no. (1 punto).

 2. Integra la aplicación en IndexedDB. Para ello deberás modificar el objeto VideoSystem que hayas implementado.
    1. Permite que, al añadir, modificar o borrar una categoría, también se haga en IndexedDB. (1 punto).
    2. Permite que, al añadir, modificar o borrar un director o un actor, también se haga en IndexedDB. (1 punto).
    3. Permite que, al añadir, modificar o borrar una producción, también se haga en IndexedDB. (2 puntos).
    4. Implementa el evento onupgradeneeded para crear la estructura necesaria de almacenes que necesites para mantener tu aplicación. Este evento deberá utilizar el método initPopulate para tener una carga inicial de objetos en la base de datos. (1,5 puntos).

 3. Para implementar el ejercicio puedes optar por dos soluciones (1,5 puntos):
    1. Dejar de utilizar los arrays para que todos los métodos de consulta de la galería se hagan contra la base de datos.
    2. Mantener los arrays, y en el onload de la página realizar todas las consultas contra la base de datos para crear la estructura de arrays que has utilizado hasta la fecha. Con esta opción por cada añadido o borrado de cualquier objeto, deberás hacerlo tanto en el array correspondiente, como en la base de datos.

## Version 1.0.0
 - Creacion del fichero IndexedBD.js
 - Añadir funcionalidad al fichero IndexedDB.js
 - Modificacion del fichero DOM.js
 - Modificacion del fichero Formularios.js