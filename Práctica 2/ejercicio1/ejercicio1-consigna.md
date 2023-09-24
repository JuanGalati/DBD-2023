# Ejercicio 1

## Consigna

Se debe modelar la información necesaria para una Inmobiliaria de la ciudad de La Plata.

Es necesario modelar la información de __clientes__ y __empleados__ de la inmobiliaria. De ambos se conoce _D.N.I_, _nombre_, _apellido_ y _dirección detallada_. Además de los __empleados__ se conoce el _número de legajo_, el cual no se repite entre diferentes empleados y el área donde trabaja cada uno.

Los empleados pueden ir rotando de __área__ a lo largo del tiempo y es necesario modelar por las distintas áreas que pasó un empleado. De las __áreas__ se conoce _código único de área_, _descripción_, _teléfonos_ y _ubicación_.

De cada cliente, además, se debe almacenar _sexo_, _nacionalidad_, _número de pasaporte_ (si tuviera) y los _inmuebles de los que es dueño_.

Un cliente no puede trabajar en la inmobiliaria.

La inmobiliaria maneja diferentes __inmuebles__ de los cuales se conoce _dirección detallada_, _código único de inmueble_, _cantidad de ambientes_, _si posee balcón_, _si posee lavadero_, _cantidad de baños_, _si se alquila, se vende o ambas cosas_, _precio de venta_ y _precio de alquiler_, _tipo de inmueble_ (casa, duplex, depto,...).

Debe quedar registrado todo alquiler y venta que realiza la inmobiliaria detallando:

* para los __alquileres__ _inmueble_, _cliente_, _fechas de inicio y fin de alquiler_, _empleado que alquiló_ y _precio_.
* De las __ventas__ se registran _fecha y hora de venta_, _cliente_, _empleado que vendió la propiedad_, _precio de venta_ y _comisión de venta_.

___Nota:__ Tenga en cuenta que podría pedirse promedio de ventas de un semestre del año, vendedor más exitoso del año, tipo de inmueble más alquilado o más vendido entre otros._
