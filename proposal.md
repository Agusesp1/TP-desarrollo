# Propuesta TP DSW

## Grupo
### Integrantes
* 54890 - Anduaga, Morena
* 52221 - España, Agustin
* 54451 - Valvasoni, Maximo
* 

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
Nuestro proyecto es desarrollar un software para la gestion de un gimnasio, permitiendo tener usuarios diferenciados(socios, profesores y encargados) los cuales van a poder interactuar con el sistema, pudiendo asistir al gimnasio por turno, administrado por el sistema, asignar rutinas a los socios, gestionar las cuotas y verificar su vencimiento, como asi tambien controlar cada usuario de una sede siendo encargado y permitiendole ver estadisticas y datos de la misma.

### Modelo

[Imagen Modelo Dominio](https://drive.google.com/file/d/1f-kPnDfZ-psf7Gbo-C4_mpzHvLksYkXz/view?usp=drive_link)


## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Sede<br>3. CRUD Actividad<br>4. CRUD Rutina|
|CRUD dependiente|1. CRUD Rutina {depende de} CRUD Socio<br>2. CRUD Sede {depende de} CRUD Encargado|
|Listado<br>+<br>detalle| 1. Listado filtrado de socios segun su estado, muestra documento, nombre y vencimiento de la cuota<br> 2. Listado de profes filtrados por sede, muestra nombre, id, especialidad|
|CUU/Epic|1. Calcular precio de cuota a un usuaroi<br>2. Generar link de pago para la cuota|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Calcular precio de cuota a un usuaroi<br>2. Generar link de pago para la cuota<br>3. Actualizar el estado del usuario|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

