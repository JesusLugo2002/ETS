# Diagrama de casos de uso - Biblioteca
<div align=center>

![img](diagrama-biblioteca.drawio.png)

</div>

## Especificación de los actores

|  Actor | Usuario |
|---|---|
| Descripción  | Persona quien irá a la biblioteca a buscar libros o devolverlos. |
| Relaciones | Con el **bibliotecario**, cada vez que presta un libro, este se lo otorga. |
| Referencias | **Buscar libro**, **Prestar libro** y **Devolver libro** |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 16 de Enero, 2024 |

|  Actor | Bibliotecario |
|---|---|
| Descripción  | Quien administra el catálogo de libros disponibles y presta los libros a los usuarios. |
| Relaciones | Con el **usuario**, al prestar un libro.  |
| Referencias | **Prestar libro** y **Actualizar catálogo** |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 16 de Enero, 2024 |


## Especificación de los casos de uso

  |  Caso de Uso	CU | Buscar libro  |
  |---|---|
  | Actor  |  Usuario |
  | Descripción | El usuario podrá buscar un libro deseado en el catálogo de la biblioteca |
  | Flujo básico | Usuario introduce nombre y/o autor del libro -> el sistema devolverá si este está disponible o no -> le presentará la opción de solicitarlo -> en caso de que sí quiera pedirlo, se le enviará la solicitud al bibliotecario. |
  | Pre-condiciones | Nombre del libro y/o autor.  |  
  | Post-condiciones  | Devolver un mensaje que indique la disponibilidad del libro deseado.  |  
  |  Requerimientos | N/A |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 16 de Enero, 2024 |
  
  |  Caso de Uso	CU | Prestar libro  |
  |---|---|
  | Actor  |  Usuario y Bibliotecario |
  | Descripción | Solicitar/otorgar el libro deseado por el usuario, de parte del bibliotecario.  |
  | Flujo básico | Usuario envía solicitud para el libro -> el bibliotecario recibe la solicitud y encuentra el libro -> se presta a usuario. |
  | Pre-condiciones | Que el libro buscado esté disponible  |  
  | Post-condiciones  | El usuario tendrá el libro por un tiempo determinado.  |  
  |  Requerimientos | El libro buscado  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 16 de Enero, 2024 |

  |  Caso de Uso	CU | Devolver libro  |
  |---|---|
  | Actor  |  Usuario |
  | Descripción | El usuario, antes, durante o después del fin de tiempo determinado, devuelve el libro a la biblioteca.  |
  | Flujo básico | El usuario llega a la biblioteca -> devuelve el libro a manos de bibliotecario o se deja en un sistema electrónico de recogida. |
  | Pre-condiciones | El usuario debe tener el libro.  |  
  | Post-condiciones  | La biblioteca volverá a tener en su inventario el libro devuelto. |  
  |  Requerimientos | El libro a devolver  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 16 de Enero, 2024 |

  |  Caso de Uso	CU | Actualizar catálogo  |
  |---|---|
  | Actor  |  Bibliotecario |
  | Descripción | El bibliotecario puede actualizar el catálogo de libros disponibles.  |
  | Flujo básico | El bibliotecario almacena la información del libro en la base de datos de la biblioteca -> guarda el libro en la estantería especificada según el código. |
  | Pre-condiciones | El libro, información sobre el mismo y sobre la posición donde debe guardarse. |  
  | Post-condiciones  | N/A |  
  |  Requerimientos | El libro |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 16 de Enero, 2024 |
