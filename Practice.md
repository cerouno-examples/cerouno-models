# Practice

## 1. Validaciones

Crear un modelo `Movie` con las siguiente características:
  - Debe tener un `name`
  - Debe tener un `length` en minutos (Que es un número)
  - Debe tener un `genre` que puede ser solamente uno de (Comedy, Drama, Action)
  - Puede tener un `review` que es un número del 0 al 5 (IE. 3.2)

## 1.2 Crear y actualizar datos

En la consola:

  - Escribe un script para crear en la base de datos todas las peliculas que se encuentran en la constante `MOVIES`.
  - Crea en la base de datos las top 3 peliculas de la cartelera de rottentomatoes.org
  - Encuentra la pelicula con el id: `2`
  - Encuentra la pelicula con el nombre: `Happy Gilmore`
  - Actualiza la pelicula con el nombre: `Saving Private Ryan` a que tenga el genre de `Drama`.

## 2. User Tweets

Crear un modelo `User`:
  - Debe tener un `username`
  - Debe tener un `first_name`
  - Debe tener un `last_name`

Creer un `Tweet`
  - Debe tener un `body` menor a 140 caracteres

* El usuario puede tener muchos tweets
* El tweet debe pertenecer a un usuario

## 3. Followers

Crear una estructura en nuestra aplicación que nos permita que:

* Un usuario pueda seguir a muchos usuarios
* Un usuario pueda ser seguido por muchos usuarios
* Debo saber la fecha en la que empecé a seguir o me empezó a seguir un usuario
