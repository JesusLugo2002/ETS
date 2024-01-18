# Diagrama de casos de uso - Gestión de tienda

![img](diagrama-gestion-tienda.drawio.png)

## Especificación de los actores

|  Actor | Cliente |
|---|---|
| Descripción  | Persona quien verá el catálogo de productos y realizará compras. |
| Relaciones | No hay relación directa con el administrador. |
| Referencias | **Ver catálogo** y **Realizar compra** |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 16 de Enero, 2024 |

|  Actor | Administrador |
|---|---|
| Descripción  | Quien gestiona el inventario de la tienda. |
| Relaciones | No hay relación directa con el cliente.  |
| Referencias | **Gestionar inventario** |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 16 de Enero, 2024 |


## Especificación de los casos de uso

  |  Caso de Uso	CU | Ver catálogo  |
  |---|---|
  | Actor  |  Cliente |
  | Descripción | El cliente podrá ver el catálogo de productos disponibles en la tienda. |
  | Flujo básico | Cliente introduce el nombre del producto que busca -> el sistema devuelve su disponibilidad -> le presentará la opción de solicitarlo -> en caso de que sí quiera pedirlo, se le enviará la solicitud al administrador un registro. |
  | Pre-condiciones | Nombre del producto  |  
  | Post-condiciones  | Devolver un mensaje que indique la disponibilidad del producto y la opción de compra  |  
  |  Requerimientos | N/A |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 16 de Enero, 2024 |
  
  |  Caso de Uso	CU | Realizar compra  |
  |---|---|
  | Actor  |  Cliente |
  | Descripción | Comprar el producto buscado en el catálogo.  |
  | Flujo básico | Cliente solicita el producto -> Lo paga con el método configurado -> Recibe el producto via correo o es llamado a buscarlo presencialmente.|
  | Pre-condiciones | Que el producto esté disponible, que haya dinero suficiente,  |  
  | Post-condiciones  | El cliente tendrá su producto. |  
  |  Requerimientos | Dinero necesario  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 16 de Enero, 2024 |

  |  Caso de Uso	CU | Gestionar inventario  |
  |---|---|
  | Actor  |  Administrador |
  | Descripción | Añadir, contabilizar y registrar productos en el inventario de la tienda  |
  | Flujo básico | El administrador lleva un registro de la entrada/salida de un producto -> Guarda el registro en el sistema de gestión. |
  | Pre-condiciones | No hay información  |  
  | Post-condiciones  | No hay información |  
  |  Requerimientos | No hay información  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 16 de Enero, 2024 |