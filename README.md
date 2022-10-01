# Proyecto Final Introducción Backend

![adaLogo](./adaImagen.png)

## Objetivo

Desarrollar una API para manejar productos de un Ecommerce, agregar productos, conseguir todos los productos, conseguir productos por id, conseguir productos por nombre, modificar productos y eliminar productos.

### Ejemplo /producto

```js
// EJEMPLO DE PRODUCTO
[
  {
    titulo: 'Foldsack mochila',
    precio: 5000,
    descripcion:
      'La mochila perfecta para el uso de todos los días, perfecto para llevar una laptop',
    categoria: 'mochilas',
    imagen: 'https://fakestoreapi.com/img/81fPKd-2AYL._AC_SL1500_.jpg',
  },
  {
    titulo: 'Biylaclesen Jacket Snowboard',
    precio: 10000,
    descripcion:
      'Campera ideal para esquiar, pero tambien se puede retirar algunas partes para ajustar a diferentes climas',
    categoria: 'camperas',
    imagen: 'https://fakestoreapi.com/img/51Y5NI-I5jL._AC_UX679_.jpg',
  },
];
```

Tambien necesitamos hacer lo mismo, un CRUD pero para una lista de emails para suscripciones

### Ejemplo /email-list

```js
[
  {
    email: 'usuario1@gmail.com',
  },
  {
    email: 'usuario2@gmail.com',
  },
];
```

### Ruta Adicional

* /status

* Tiene que devolver OK, para saber que mi backend esta funcionando.

### Public Page

* En la carpeta page esta la página que nuestro backend tiene que dar. 

![suscripciones](./suscripcion.jpg)

## Tecnologias

* Utilizar Nodejs y Express

* Base de datos MongoDB con Mongoose

* Otras librerias, Dotenv, Cors y Morgan

El codigo tiene que estar en github en un repositorio con un README.md explicando el proyecto y como ejecutarlo

## Despliegue

* El Backend tiene que correr en Railway

* Base de datos en Mongodb Atlas
