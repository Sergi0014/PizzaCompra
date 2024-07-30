# Proyecto de Compra de Pizzas

Este proyecto es una aplicación web para la compra de pizzas. Los usuarios pueden ver un menú de pizzas, agregar pizzas a su carrito y enviar un formulario de contacto.

## Tecnologías Utilizadas

- **React**: Biblioteca de JavaScript para construir interfaces de usuario.
- **CSS**: Para el diseño y estilo de la aplicación.
- **JavaScript**: Lenguaje de programación utilizado para la lógica de la aplicación.

## Estructura del Proyecto

El proyecto está organizado en varios componentes y páginas:

### Componentes

- **MenuItem**: Representa un ítem del menú de pizzas. Muestra la imagen, el nombre y el precio de la pizza, y tiene un botón para agregar la pizza al carrito.
- **MenuList**: Lista de objetos que representan las pizzas disponibles en el menú.

### Páginas

- **App**: Componente principal de la aplicación. Contiene el estado del carrito y maneja la lógica para agregar pizzas al carrito.
- **Menu**: Página que muestra el menú de pizzas. Utiliza el componente `MenuItem` para mostrar cada pizza y permite agregar pizzas al carrito.
- **Contact**: Página de contacto que contiene un formulario para que los usuarios envíen sus mensajes.

## Funcionalidades

### Menú de Pizzas

Los usuarios pueden ver una lista de pizzas disponibles en el menú. Cada pizza muestra su imagen, nombre y precio. Los usuarios pueden agregar pizzas al carrito haciendo clic en el botón "Agregar al carrito".


### Formulario de Contacto

La página de contacto contiene un formulario donde los usuarios pueden ingresar su nombre, email y un mensaje. El formulario se envía utilizando el método POST.
