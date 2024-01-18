# Diagrama de casos de usos - Reserva de vuelos

<div align=center>

![img](diagrama-reservas.drawio.png)

</div>

## Especificación de actores


|  Actor | Pasajero |
|---|---|
| Descripción  | Persona que puede buscar vuelos para reservar. |
| Características  | No hay información |
| Relaciones | Al cancelar reserva, esta es procesado por el agente.  |
| Referencias | CU-01, CU-03 |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 18 de Enero, 2024 |

|  Actor | Agente de reservas |
|---|---|
| Descripción  | Quien tiene capacidad para cancelar vuelos y reservar en el sistema.  |
| Características  | No hay información |
| Relaciones | Procesa las cancelaciones de reserva por parte de los pasajeros. |
| Referencias | CU-02, CU-03 |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 18 de Enero, 2024 |

## Especificación de casos de uso

|  Caso de Uso CU-01 | Buscar vuelo  |
  |---|---|
  | Actor  | Pasajero |
  | Descripción | El cliente podrá buscar en el sistema de gestión los vuelos junto a sus destinos y precios.  |
  | Flujo básico | El usuario entra en el sistema y realiza la búsqueda -> se muestra los vuelos disponibles -> presenta la opción de reservar vuelo. |
  | Pre-condiciones | No hay información |  
  | Post-condiciones  | Genera la reserva del vuelo asignado al pasajero |  
  |  Requerimientos | N/A |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 18 de Enero, 2024 |
  
  |  Caso de Uso CU-02 | Cancelar vuelo  |
  |---|---|
  | Actor  |  Agente de reservas |
  | Descripción | El administrador del sistema podrá, tras cancelar la reserva, cancelar el vuelo de un pasajero  |
  | Flujo básico | No hay información |
  | Pre-condiciones | Que exista una reserva  |  
  | Post-condiciones  | El vuelo es cancelado  |  
  |  Requerimientos | No hay información  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 18 de Enero, 2024 |

  |  Caso de Uso CU-03 | Cancelar reserva  |
  |---|---|
  | Actor  |  Pasajero y agente de reserva|
  | Descripción | Tanto el pasajero como el agente de reserva puede cancelar reservas del sistema.  |
  | Flujo básico | No hay información |
  | Pre-condiciones | Debe existir una reserva |  
  | Post-condiciones  | Reserva cancelada |  
  |  Requerimientos | No hay información |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 18 de Enero, 2024 |