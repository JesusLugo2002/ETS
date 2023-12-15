# Ciclos de vida del Software

## Modelo 'Cascada'

En **Ingeniería de software** el desarrollo en cascada, también llamado *secuencial o ciclo de vida* de un programa (denominado así por la posición de las fases en el desarrollo de esta, que parecen caer en cascada “por gravedad” hacia las siguientes fases), es el enfoque metodológico que ordena rigurosamente las etapas del proceso para el desarrollo de software, de tal forma que el inicio de cada etapa debe esperar a la finalización de la etapa anterior.​ Al final de cada etapa, el modelo está diseñado para llevar a cabo una revisión final, que se encarga de determinar si el proyecto está listo para avanzar a la siguiente fase. Este modelo fue el primero en originarse y es la base de todos los demás modelos de ciclo de vida. 

<div align=center>
<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/El_modelo_de_desarrollo_en_cascada.svg/1280px-El_modelo_de_desarrollo_en_cascada.svg.png' width=70%/>
</div> 

En la práctica, se aplican diversas versiones del modelo. Los más habituales son los modelos que dividen los procesos de desarrollo en cinco fases. En ocasiones, las fases 1, 2 y 3 definidas por Royce se integran en una sola fase de proyecto a modo de análisis de los requisitos.

1. **Análisis**: planificación, análisis y especificación de los requisitos.
2. **Diseño**: diseño y especificación del sistema.
3. **Implementación**: programación y pruebas unitarias.
4. **Verificación**: integración de sistemas, pruebas de sistema y de integración.
5. **Mantenimiento**: entrega, mantenimiento y mejora.

### Realimentación en el modelo 'cascada'

Sin embargo, el modelo cascada en algunas de sus variantes es uno de los actualmente más utilizados, por su eficacia y simplicidad, más que nada en software de pequeño y algunos de mediano porte; pero nunca (o muy rara vez) se lo usa en su «forma pura», como se dijo anteriormente. En lugar de ello, siempre se produce alguna realimentación entre etapas, que no es completamente predecible ni rígida; esto da oportunidad al desarrollo de productos software en los cuales hay ciertas incertezas, cambios o evoluciones durante el ciclo de vida. Así por ejemplo, una vez capturados y especificados los requisitos (primera etapa) se puede pasar al diseño del sistema, pero durante esta última fase lo más probable es que se deban realizar ajustes en los requisitos (aunque sean mínimos), ya sea por fallas detectadas, ambigüedades o bien por que los propios requisitos han cambiado o evolucionado; con lo cual se debe retornar a la primera o previa etapa, hacer los reajuste pertinentes y luego continuar nuevamente con el diseño; esto último se conoce como realimentación. Lo normal en el modelo cascada será entonces la aplicación del mismo con sus etapas realimentadas de alguna forma, permitiendo retroceder de una a la anterior (e incluso poder saltar a varias anteriores) si es requerido.

## Modelos evolutivos

