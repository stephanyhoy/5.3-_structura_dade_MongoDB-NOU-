# Óptica - Base de Datos en MongoDB

Este proyecto describe el diseño y la implementación de una base de datos en MongoDB para gestionar los clientes, proveedores, empleados y las ventas de una óptica llamada "Culo de Botella".

Descripción del Proyecto:

La óptica necesita informatizar la gestión de los clientes, proveedores y ventas de gafas. La base de datos debe almacenar información relevante sobre cada una de estas entidades y sus relaciones.

| **Colecciones** |    **Atributos**                                                                                                |
|-------------|----------------------------------------------------------------------------------------------|
| Proveedores | Nombre, Dirección (calle, número, piso, puerta, ciudad, código postal, país), Teléfono, Fax, NIF |
| Gafas       | Marca, Graduación de vidrios, Tipo de montura (flotante, pasta o metálica), Color de montura, Color de vidrios, Precio |
| Clientes    | Nombre, Dirección postal, Teléfono, Correo electrónico, Fecha de registro, Cliente recomendador (si lo hay) |
| Ventas      | Empleado que realizó la venta, Fecha y hora de la venta                                       |


## Ejercicio 1

Imagina que tenemos la siguiente interfaz gráfica, desde el punto de vista de un cliente de la Óptica. ¿Cómo diseñarías la base de datos que facilitara la información?

![Interfaz gráfica](./Imagen1PHP.jpg)


## Ejercicio 2

¿Y si el punto de vista de la interfaz fueran las gafas?

![Interfaz gráfica](./Imagen2PHP.jpg)
