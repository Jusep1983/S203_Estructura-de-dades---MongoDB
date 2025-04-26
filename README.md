# S203_Estructura-de-dades---MongoDB

## 📄 Descripción
Este repositorio contiene el diseño de bases de datos en MongoDB para dos casos prácticos: la gestión de clientes y ventas de una óptica y la creación de una web para pedidos de comida a domicilio. El objetivo es modelar las estructuras de datos en bases de datos NoSQL.

## 🔽 Enunciados:

<details>
<summary> 
Nivel 1 (clica en el desplegable para el enunciado completo)
  
</summary>
  
  ## Ejercicio 1 - Òptica  
  Una óptica llamada "Cul d'Ampolla" quiere informatizar la gestión de clientes y ventas de gafas.  
  Los requisitos son los siguientes:
  
  - **Proveedores:** Nombre, dirección (calle, número, piso, puerta, ciudad, código postal y país), teléfono, fax, NIF.
  - **Ulleres:** Marca, graduación de cada lente, tipo de montura (flotante, pasta o metálica), color de la montura, color de cada lente y precio.
  - **Clientes:** Nombre, dirección postal, teléfono, correo electrónico, fecha de registro.
  - **Recomendaciones:** En caso de que un cliente haya sido recomendado por otro, guardar quién fue la persona que lo recomendó.
  - **Empleados:** Almacenar quién vendió cada gafas y cuándo ocurrió la venta.

  ## Ejercicio 2 - Ulleres  
  ¿Y si el punto de vista de la interfaz fuera las gafas? ¿Cómo modelarías la base de datos?

</details>

<details>
<summary> 
  Nivel 2 (clica para ver el enunciado completo)
  
</summary>
  
  ## Ejercicio 1 - Pedido de Comida a Domicilio  
  Se ha contratado para diseñar la base de datos de una web que permita realizar pedidos de comida a domicilio.  
  Los requisitos para el modelo de base de datos son los siguientes:
  
  - **Clientes:** Cada cliente tiene un identificador único y se almacena su nombre, apellidos, dirección, código postal, localidad, provincia y teléfono.
  - **Comandas:** Cada comanda tiene un identificador único y se almacena la fecha/hora de realización, tipo de comanda (domicilio o recoger en tienda), la cantidad de productos de cada tipo, el precio total y una nota adicional.
  - **Productos:** Pueden ser pizzas, hamburguesas o bebidas. Cada producto tiene un identificador único, nombre, descripción, imagen y precio. Las pizzas pueden pertenecer a varias categorías.
  - **Tiendas:** Cada tienda tiene un identificador único y se almacena su dirección, código postal, localidad y provincia.
  - **Empleados:** Cada empleado tiene un identificador único y se almacena su nombre, apellidos, NIF, teléfono y su rol (cocinero o repartidor).  
  - **Repartidores:** Almacenamos quién es el repartidor asignado a cada pedido y la fecha/hora de la entrega.

</details>

## 💻 Tecnologías Utilizadas

El proyecto ha sido desarrollado utilizando:

- MongoDB como sistema gestor de base de datos
- MongoDB Compass como herramienta de diseño y ejecución de scripts
- Git y GitHub para control de versiones

## 📋 Requisitos

Para ejecutar el proyecto es necesario contar con:

- MongoDB Server
- MongoDB Compass u otra herramienta compatible con MongoDB
- Git instalado

## 🛠️ Instalación

Clona el repositorio:

- git clone:   https://github.com/Jusep1983/S203_Estructura-de-dades---MongoDB.git

- Abre MongoDB Compass u otra herramienta compatible.

- Ejecuta los scripts para crear las colecciones y relaciones de datos.

## ▶️ Ejecución

Ejecuta las consultas de verificación que encontrarás en cada nivel para comprobar la integridad de las relaciones y datos insertados.

## 🌐 Despliegue

Este proyecto está pensado para entorno local. No se contempla despliegue online.

## 🤝 Contribuciones

Si deseas colaborar, puedes:

- Abrir una issue con sugerencias o problemas detectados
- Hacer un fork y luego una pull request con tus propuestas de mejora

¡Gracias por tu interés en este proyecto! 🚀
