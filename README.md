# Proyecto Inicial

## Idea a Implementar

La idea es implementar un conjunto de aplicaciones que permitan visualizar trailers de películas e información adicional sobre estas.


## Diagrama ER

![Trailerama ER](https://user-images.githubusercontent.com/54337526/159197194-1c6b7d0b-ff90-43ca-8b89-0226b64b7926.jpg)


## Actualizaciones a los datos
>
El proyecto Framework PHP - Laravel permitirá:

A usuarios con el rol de usuario:
 - Guardar una película como vista.
 - Puntuar una película.
 - Dejar un comentario.

A usuarios con el rol de administrador:
 - Administrar usuarios.
 - Añadir/eliminar/modificar una películas y sus datos.
 - Crear tags que se pueden añadir a una película.
 - Crear una lista de recomendación semanalmente.

Además se cargarán a la base de datos distintas críticas a las películas por medio de apis.


## Información del Servicio Web

El servicio web permitirá acceder a las distintas películas con el siguiente campo:
 - Nombre.

Además el servicio también permitirá acceder a las distintas películas utilizando filtros con uno o más de los siguientes campos:
 - Nombre.
 - Fecha de publicación.
 - Puntuacion.
 - Tags.
 - Vistas.

El servicio también permitirá acceder a las listas de recomendaciones anteriores o de la semana actual.
	
El servicio permitirá acceder a los comentarios realizados en las películas y sus críticas.


## Visualización y Acceso a la Información

Proyecto Javascript-React:
 - Permitirá al usuario ingresar una búsqueda de películas, permitiendo agregar filtros de manera iterativa y amigable.
 - Además mostrará las recomendaciones de películas, películas relacionadas y sugerencias de donde podría mirarlas.
 - Se podrá buscar películas que se hayan estrenado recientemente o que no se han estrenado aún.


