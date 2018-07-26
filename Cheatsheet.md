# Cheat Sheet

## Línea de comandos Rails:

Todos estos comandos se ejecutan en el folder de la aplicación Rails:

### Crear un modelo

`rails g model [Model] [attribute]:[type] ...`

IE.

`rails g model Person name:string age:integer dob:date salary:float likes_cats:boolean`

### Ejecutar las migraciones

`rails db:migrate`

### Rollback de las migraciones

`rails db:rollback`

### Empezar el servidor

`rails server`

### Empezar la consola

`rails console`

## Básicos

### Buscar por id

`Person.find(1)`

### Buscar por algun atributo

`Person.find_by(name: 'Adrian')`

### Crear un modelo

`Person.create(name: 'Adrian')`

### Cambiar un modelo

```
person = Person.find(1)
person.name = 'Adri'
person.save
```

### Actualizar un modelo directamente

```
person = Person.find(1)
person.update(name: 'Adrian')
```

### Eliminar un Modelo

```
person = Person.find(1)
person.destroy
```

## Validaciones y relaciones

* [Validaciones](https://api.rubyonrails.org/classes/ActiveModel/Validations/ClassMethods.html#method-i-validates)
* Relaciones:
  * [Belongs To](https://api.rubyonrails.org/classes/ActiveRecord/Associations/ClassMethods.html#method-i-belongs_to)
  * [Has Many](https://api.rubyonrails.org/classes/ActiveRecord/Associations/ClassMethods.html#method-i-has_many)
  * [Has and Belongs To Many](https://api.rubyonrails.org/classes/ActiveRecord/Associations/ClassMethods.html#method-i-has_and_belongs_to_many)
