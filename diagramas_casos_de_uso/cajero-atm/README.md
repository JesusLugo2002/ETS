# Diagrama de casos de uso - Cajero ATM

<div align=center>

![img](./diagrama-casos-uso-atm.drawio.png)

</div>

<div align=justify>

## Índice
- [Especificación de actores](#especificación-de-actores)
    - [Cliente bancario](#actor-cliente-bancario)
    - [Administrador](#actor-administrador)
- [Especificación de casos de uso](#especificación-de-actores)
    - [Ingresar dinero](#ingresar-dinero)
    - [Hacer transferencia](#hacer-transferencia)
    - [Poner dinero al movil](#poner-dinero-al-movil)
    - [Login](#login)
    - [Registrar movimiento](#registrar-movimiento)

<table>
  <tr><th>Paso</th><th>Acción</th></tr>
  <tr><td>1</td><td>Paranguatutirimicuaro</td></tr>
  <tr><td>2</td><td>Paranguatutirimicuaro</td></tr>
  <tr><td>3</td><td>Paranguatutirimicuaro</td></tr>
</table>

## Especificación de actores

### Actor 'Cliente bancario'

|  Actor cuqui | Cliente bancario |
|---|---|
| Descripción  | Aquella persona que contrata un producto o servicio con una entidad financiera.  |
| Relaciones | En el diagrama de casos de uso actual no se encuentra ninguna relación directa con otro actor. |
| Referencias | CU-01, CU-02, CU-03, CU-04 |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 25 de Enero, 2024 |

### Actor 'Administrador'

|  Actor cuqui| Administrador |
|---|---|
| Descripción  | Persona que gestiona los movimientos de entrada/salida del sistema de cajero. |
| Relaciones | En el diagrama de casos de uso actual no se encuentra ninguna relación directa con otro actor. |
| Referencias | CU-05 |   
| Autor  | Jesús Daniel Lugo López |
|Fecha | 25 de Enero, 2024 | 

## Especificación de casos de uso

### Ingresar dinero

  |  Caso de Uso	CU-01 | Ingresar dinero  |
  |---|---|
  | Actor  |  Cliente bancario |
  | Descripción | El cliente ingresa cierta cantidad de dinero en su cuenta bancaria  |
  | Flujo básico | <table><tr><th>Paso</th><th>Acción</th></tr><tr><td>1</td><td>El cliente ingresa en el sistema la cantidad de dinero a depositar.</td></tr><tr><td>2</td><td>El cliente ingresa el dinero en efectivo.</td></tr><tr><td>3</td><td>El sistema devuelve dinero si hace falta.</td></tr><tr><td>4</td><td>Se cierra el depósito en el sistema.</td></tr></table> |
  | Flujo alternativo | <table><tr><th>Paso</th><th>Acción</th></tr><tr><td>2</td><td>Si el dinero que el cliente ingresa es insuficiente...</td></tr><tr><td></td><td>A.1. El sistema devuelve todo el dinero y se cierra el caso de uso.</td></tr></table> |
  | Pre-condiciones | El cliente debe haberse autenticado en el sistema. |  
  | Post-condiciones  | El dinero es depositado en la cuenta bancaria.  |  
  |  Requerimientos | Dinero en efectivo |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 25 de Enero, 2024 |

### Hacer transferencia

  |  Caso de Uso	CU-02 | Hacer transferencia  |
  |---|---|
  | Actor  |  Cliente bancario |
  | Descripción | El cliente realiza una transferencia a otra cuenta bancaria. |
  | Flujo básico | <table><tr><th>Paso</th><th>Acción</th></tr><tr><td>1</td><td>El cliente ingresa el identificador de la otra cuenta bancaria.</td></tr><tr><td>2</td><td>El cliente ingresa la cantidad de dinero a transferir.</td></tr></table> |
  | Pre-condiciones | <table>
  <tr><th>Paso</th><th>Acción</th></tr>
  <tr><td>1</td><td>Si el identificador no existe/está mal escrito...</td></tr>
  <tr><td>2</td><td>Paranguatutirimicuaro</td></tr>
  <tr><td>3</td><td>Paranguatutirimicuaro</td></tr>
</table> |  
  | Post-condiciones  | _Que debe ocurrir con posterioridad_  |  
  |  Requerimientos | _Que debe de exister para que el caso de uso se ejecute. Ej: Tarjeta de crédito_  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 25 de Enero, 2024 |

### Poner dinero al movil

  |  Caso de Uso	CU-03 | Poner dinero al movil  |
  |---|---|
  | Actor  |  Cliente bancario |
  | Descripción | _Descripción del caso de uso_  |
  | Flujo básico | _Descripción paso a paso de la ejecución. (1->2->3.)_ |
  | Pre-condiciones | _Que debe ocurrir con anterioridad_  |  
  | Post-condiciones  | _Que debe ocurrir con posterioridad_  |  
  |  Requerimientos | _Que debe de exister para que el caso de uso se ejecute. Ej: Tarjeta de crédito_  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 25 de Enero, 2024 |

### Login

  |  Caso de Uso	CU-04 | Login  |
  |---|---|
  | Actor  |  Cliente bancario |
  | Descripción | _Descripción del caso de uso_  |
  | Flujo básico | _Descripción paso a paso de la ejecución. (1->2->3.)_ |
  | Pre-condiciones | _Que debe ocurrir con anterioridad_  |  
  | Post-condiciones  | _Que debe ocurrir con posterioridad_  |  
  |  Requerimientos | _Que debe de exister para que el caso de uso se ejecute. Ej: Tarjeta de crédito_  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 25 de Enero, 2024 |

### Registrar movimiento

  |  Caso de Uso	CU-05 | Registrar movimiento  |
  |---|---|
  | Actor  |  Administrador |
  | Descripción | _Descripción del caso de uso_  |
  | Flujo básico | _Descripción paso a paso de la ejecución. (1->2->3.)_ |
  | Pre-condiciones | _Que debe ocurrir con anterioridad_  |  
  | Post-condiciones  | _Que debe ocurrir con posterioridad_  |  
  |  Requerimientos | _Que debe de exister para que el caso de uso se ejecute. Ej: Tarjeta de crédito_  |
  | Autor  | Jesús Daniel Lugo López |
  |Fecha | 25 de Enero, 2024 |

</div>