# Practice

## 1. Validaciones

Crear un modelo `Movie` con las siguiente características:
  - Debe tener un `name`
  - Debe tener un `length` en minutos (Que es un número)
  - Debe tener un `gender` que puede ser solamente uno de (Comedy, Drama, Documentary)
  - Puede tener un `review` que es un número del 0 al 5 (IE. 3.2)

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
