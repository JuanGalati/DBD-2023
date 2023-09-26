# Ejercicio 2

### Contexto
Se desea modelar la información necesaria para una red social. 

### Entidades
Usuarios
* nombre y apellido, 
* usuario en la red social (que es único), 
* clave de acceso, 
* cuentas de correo electrónico, 
* dirección detallada y 
* un teléfono de contacto.

Publicaciones
* Imágenes
  * Fecha
  * Hora
  * Temática
  * Título
  * Usuario
  * Nombre de archivo
  * Etiquetas

Vínculo
* Fecha
* Hora
* Tipo
* Descripción (opcional): lugar del vínculo

Temática
* nombre único
* descripción

Comentario
*  texto, 
*  fecha y hora de creación, 
*  que imagen comentó o a que comentario respondió

### Entidades (resumen)
* Usuarios
* Publicaciones
  * Imágenes
* Vínculo
* Temática
* Comentario





### Relaciones
* Usuarios publican Publicaciones
* Usuarios comentan Contenidos
* Usuarios descargan Publicaciones
* Usuarios comparten Publicaciones
* Usuarios vinculan Usuarios 

### Restricciones
* Usuarios
  * Un usuario no puede subir dos imágenes con título idéntico. 
  * Un usuario no podrá realizar dos comentarios en la misma fecha y hora.
* Publicaciones
  * Comentarios
  * Imágenes
    * Un usuario no puede subir dos imágenes con título idéntico.
* Vínculo
  * En la misma fecha y hora el mismo usuario no podrá generar dos vínculos.
* Comentario
  * Un usuario no podrá realizar dos comentarios en la misma fecha y hora.
