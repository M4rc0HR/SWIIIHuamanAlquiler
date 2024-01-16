# SWIIIHuamanAlquiler
## Identificacion de subdominos
### Gestion de alquileres
Es un dominio del tipo CORE, esto porque es el giro principal del negocio que trata sobre el alquilar vehiculos a los clientes.
### Gestion de Clientes
Es un dominio de tipo SOPORTTE, esto porque es necesario para generar valor del negocio, pero no lo suficiente como el de Alquileres, ya que funciona como ayuda al mismo (Alquileres), para obtener una ventaja estrategica.
### Gestion de Vehiculos
Es un dominio de tipo SOPORTTE, esto porque es necesario para generar valor del negocio, pero no lo suficiente como el de Alquileres, ya que funciona como ayuda al mismo (Alquileres), para obtener una ventaja estrategica con la informacion de los vehiculos que se obtienen.
### Gestion de Pagos
Es un dominio de tipo SOPORTTE, esto porque es necesario para llevar a cabo el proceso de alquiler correctamente, de esta forma generando valor al ayudar al subdomino alquileres, pero no por si mismo.
### Seguridad
Es un dominio de tipo GENERICO, esto porque no proporciona un valor unico al negocio, sino que es usado por diversos negocios para un mismo fin.


## Identificacion de BoundedContext

- BoundedContext GestionAlquileres
- BoundedContext GestionClientes
- BoundedContext GestionVehiculos
- BoundedContext GestionPagos
- BoundedContext Seguridad
