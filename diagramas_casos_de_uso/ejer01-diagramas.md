# Ejercicio de tablas sobre un diagrama de casos de uso

<div align=center>

![img](img/diagrama.png)

</div>

Tomando en cuenta el diagrama visto en la clase, las tablas que definen los actores y los casos de usos son:

## Actores

|  Actor | Administrador |
|---|---|
| Descripción  | Persona cuyos privilegios son utilizados para administrar la aplicación del diagrama de casos de uso. |
| Características  | Capacidad para definir y manejar la información contenida en la aplicación |
| Relaciones | Se relaciona con el **usuario** cuando realiza la *alta y baja de usuarios*.  |
| Referencias | *Definir medio de transporte*, *Definir precio de transporte*, *Alta y baja de usuarios*. |   
|  Notas | *No hay* |
| Autor  | Jesús Daniel Lugo López |
|Fecha | 9 de Enero, 2024 |

|  Actor | Usuario |
|---|---|
| Descripción  | Cliente de la aplicación  |
| Características  | Acceso a la verificación de credenciales, geoposicionamiento y la definición de rutas y destinos. |
| Relaciones | En la *alta y baja de usuarios*, con el **administrador**.  |
| Referencias | *Alta y baja de usuarios*, *Login y verificación de credenciales*, *Geoposicionamiento*, *Definir destino* y *Modificar rutas*. |   
|  Notas |  *Tampoco hay* |
| Autor  | Jesús Daniel Lugo López |
|Fecha | 9 de Enero, 2024 |

## Casos de uso

|  Caso de Uso	CU | Definir medio de transporte  |
  |---|---|
  | Fuentes  | No hay información |
  | Actor  |  Administrador |
  | Descripción | Definición del medio de transporte |
  | Flujo básico | No hay información |
  | Pre-condiciones | No hay |  
  | Post-condiciones  | No hay información  |  
  |  Requerimientos | No hay información   |
  |  Notas |  No hay |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 9 de Enero, 2024 |

|  Caso de Uso	CU | Definir precio de transporte  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Administrador |
  | Descripción | Definición del precio de transporte  |
  | Flujo básico | No hay información  |
  | Pre-condiciones | No hay información   |  
  | Post-condiciones  | No hay información   |  
  |  Requerimientos | No hay información   |
  |  Notas |  No hay información  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 9 de Enero, 2024 |

|  Caso de Uso	CU | Alta y baja de usuarios  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Administrador y usuario |
  | Descripción | Creación y eliminación de usuarios del sistema de la aplicación  |
  | Flujo básico | No hay información  |
  | Pre-condiciones | No hay información   |  
  | Post-condiciones  | No hay información   |  
  |  Requerimientos | No hay información   |
  |  Notas |  No hay información  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 9 de Enero, 2024 |

|  Caso de Uso	CU | Login  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Usuario |
  | Descripción | Método de acceso al sistema de la aplicación |
  | Flujo básico | No hay información  |
  | Pre-condiciones | No hay información   |  
  | Post-condiciones  | Verificar credenciales   |  
  |  Requerimientos | No hay información   |
  |  Notas |  No hay información  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 9 de Enero, 2024 |

|  Caso de Uso	CU | Verificar credenciales  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Usuario |
  | Descripción | Verificación de credenciales  |
  | Flujo básico | No hay información  |
  | Pre-condiciones | Login  |  
  | Post-condiciones  | No hay información   |  
  |  Requerimientos | Información dada por el 'Login' |
  |  Notas |  No hay información  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 9 de Enero, 2024 |

|  Caso de Uso	CU | Geoposicionamiento  |
  |---|---|
  | Fuentes  | No hay información |
  | Actor  |  Usuario |
  | Descripción | Estimación de la posición geográfica del cliente/destino. |
  | Flujo básico | No hay información |
  | Pre-condiciones | No hay información  |  
  | Post-condiciones  | Debe estar relacionado con un sistema externo de geoposicionamiento.  |  
  |  Requerimientos | No hay información  |
  |  Notas |  No hay información |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 11 de Enero, 2024 |

|  Caso de Uso	CU | Definir destino  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Usuario |
  | Descripción | Función de la aplicación para definir el destino deseado del cliente  |
  | Flujo básico | No hay información |
  | Pre-condiciones | No hay información  |  
  | Post-condiciones  | No hay información  |  
  |  Requerimientos | No hay información  |
  |  Notas |  No hay información |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 11 de Enero, 2024 |

|  Caso de Uso	CU | Sugerir destinos interesantes  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Usuario |
  | Descripción | Mostrar al cliente sugerencias de destinos interesantes  |
  | Flujo básico | No hay información |
  | Pre-condiciones | El usuario debe pulsar un botón _destinos interesantes_  |  
  | Post-condiciones  | No hay información  |  
  |  Requerimientos | No hay información  |
  |  Notas |  No hay información |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 11 de Enero, 2024 | 

|  Caso de Uso	CU | Mostrar puntos de interés en la ruta  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Usuario |
  | Descripción | Mostrar al usuario puntos de interés en la ruta marcada al definir un destino.  |
  | Flujo básico | No hay información |
  | Pre-condiciones | El usuario debe pulsar un botón _ptos. de interés en ruta_ |   
  | Post-condiciones  | No hay información  |  
  |  Requerimientos | No hay información  |
  |  Notas |  No hay información |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 11 de Enero, 2024 |

|  Caso de Uso	CU | Modificar ruta  |
  |---|---|
  | Fuentes  | No hay información  |
  | Actor  |  Usuario|
  | Descripción | Modificación de la ruta elegida por el usuario |
  | Flujo básico | No hay información |
  | Pre-condiciones | No hay información  |  
  | Post-condiciones  | No hay información  |  
  |  Requerimientos | No hay información  |
  |  Notas |  No hay información |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 11 de Enero, 2024 |