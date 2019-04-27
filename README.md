# Amoblando Tu Hogar
## Integrantes:
Carlos Andres Alvarez
John Jairo Vargas

## Descripción:
Se inicia la creación del proyecto Amoblando Tu Hogar, en este espacio se guardarán los avances del desarrollo del aplicativo:

crear un proyecto siguiendo las siguientes etapas de desarrollo.
 
1-) Creación de un repositorio en GitHub para alojar solo la codificación del sistema.
2-) creación de la base de datos que dará solución a la problemática planteada.
3-) creación de los respectivos Mockups de la página web (inicio, quienes somos, productos, iniciar  sesión, regístrate, etc) 
4-) creación de los mockups de la página del administrador. (interfaz Admin).
5-) codificación de los mockups (HTML, CSS,JAVASCRIPT,PHP).
6-) codificación de la página del administrador (solo FrontEnd) creación de las vistas.
7-) creación de un inicio sesión perfectamente realizado y validado
8-) creación del formulario de registro que inserte datos a la base de datos de forma correcta (datos del usuario o cliente).
9-) back end de toda la gestión interna descrita en el planteamiento del problema.
10-)uso de la librería fpdf.

Planteamiento del problema
 
la empresa de muebles amoblando tu hogar esta en busca del desarrollo de una página web donde sus clientes puedan encontrar la siguiente información.
 
1-) número de contacto de los asesores.
2-) direcciones o ubicaciones de los lugares donde puede ser atendido.
3-) productos (salas, alcobas, comedores y sillas).
4-) precios de los productos.
5-) promociones y descuentos.
6-) métodos de pago.
 
para ello usted deberá desarrollar el respectivo sistema de información dando solución a los requerimientos del cliente.
 
 
después de haber desarrollado de interfaz para los usuarios el cliente solicita un espacio donde el pueda gestionar la cantidad de productos que tiene (agregar, editar, eliminar y consultar productos).
 
1-) el administrador del sistema puede crear un nuevo producto. (todos los productos deben tener su respectiva imagen).
2-) el administrador del sistema puede editar un nuevo producto.
3-) el administrador del sistema puede editar un eliminar producto.  
4-) el administrador del sistema puede consultar todos los productos.
5-) el administrador cuenta con un stock de los productos.
6-) el administrador puede agregar y eliminar datos del stock.
7-) el administrador realiza una venta a un usuario solo si el usuario esta registrado en el sistema.
8-) al realizar la venta de ejemplo 2 sillas se debe de evidenciar esa sustracción de 2 sillas en el stock.
9-) para que el administrador pueda realizar actividades de gestión de información debe de estar logeado en el sistema, si no esta logeado el sistema no debe permitir la gestión de la información. 
10-) el cliente podrá realizar la descarga de la factura de la compra con el solo documento o correo.
11-) la factura de la compra debe estar hecha en fpdf y debe retornar los siguientes datos (nombre de la tienda, logo , fecha de la venta, nombre del cliente, nombre del administrador, productos que compro precio de cada producto y total de la factura).
12-) el administrador puede ver el historial de las ventas realizadas en el sistema de información. 
13-) un administrador puede registrar otro administrador
14-) la cantidad de roles manejados en el sistema de información serán (cliente, administrador).
 
Datos de los clientes.
 
nombres
apellidos
correo
tipo documento
documento
genero
ciudad
contraseña
 
Datos de los productos
nombre
descripción
precio
descuento
peso
alto
ancho
cantidad
 
Datos del administrador
nombres 
apellidos
correo
documento
contraseña
