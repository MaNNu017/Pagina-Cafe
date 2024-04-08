# Propuesta TP DSW

## Grupo
### Integrantes
* 49693 - Coccoz, Manuel

### Repositorios
* [fullstack app](https://github.com/MaNNu017/fullstack-app)

## Tema
### Descripción
Pagina web de un cafe online, donde los usuarios/clientes podran ver todos los productos disponibles para la venta, agregar productos al carrito y hacer pedidos online para entrega a domicilio.

### Modelo
![imagen del modelo](https://github.com/MaNNu017/Pagina-Cafe/blob/main/modelocafe.png)

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 1 integrante para un sistema de cafeteria.  

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Pedido<br>|
|CRUD dependiente|1. CRUD Producto {depende de} CRUD Tipo Categoría|
|Listado<br>+<br>detalle| 1. Listado de productos filtrado por categoría del producto  => detalle CRUD Producto<br> |
|CUU/Epic|1. Realizar una compra de productos|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
