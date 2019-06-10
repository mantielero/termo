# Primera ley de la termodinámica
La primera ley (o primer principio) de la termodinámica nos lleva a la **ley de conservación de la energía**.

El **primer principio de la termodinámica** dice que el cambio de energía de un sistema es igual a la diferencia entre el calor añadido al sistema y el trabajo realizado por el sistema:
$$
\Delta E = Q-W \qquad \text{[J]}
$$
en donde:

- $E$: energía del sistema
- $Q$: calor que entra al sistema
- $W$: trabajo realizado por el sistema

Pero, ¿qué es la energía? ¿qué el calor? ¿qué es el trabajo?

!!! note
    Esto es fruto de la observación.

!!! note
    Si lo expresamos por unidad másica:
    $$
    \Delta e = q- w \qquad \left[\frac{J}{kg}\right]
    $$

!!! danger
    Esta fórmula sólo es aplicable a sistemas cerrados.

## Energía
Para todo sistema existe una propiedad llamada *energía*, $E$ que es suma de:

- energía interna ($u$)
- energía cinética (se ve en física)
- energía potencial (se ve en física)
- energía química (casi nunca se tiene en cuenta).

$$
E = U +  E_{cinética} + E_{potencial} + ...
$$


!!! note
    La *ley cero* definía la propiedad: *temperatura*. La primera ley define una nueva propiedad: *energía*.

## Trabajo
### Punto de vista de la Mecánica
En mecánica, el trabajo se define como el producto de la fuerza por el desplazamiento de su punto de aplicación. Para un desplazamiento diferencial, se tiene:
$$
\delta W = F_s ds = \vec F \cdot \vec{dr} = \overline{F} \cdot \overline{v} dt
$$

En el primer caso:
- $F_s$: es la componente de la fuerza paralela a la trayectoria
- $ds$: el desplazamiento a lo largo de la trayectoria

mientras que:
- $\vec{F}$: vector fuerza
- $\vec{dr}$: variación del vector de posición.

Para calcular el trabajo, involucrado en un proceso finito habría que realizar la integral a lo largo de la trayectoria, por lo que se tendría que conocer la relación funcional ($F$, $s$) o ($\vec{F}$, $\vec{dr}$).
### Punto de vista Termodinámica
Se denomina **trabajo** ($W$) a la interacción entre sistema y medio ambiente que, cuando es realizada por el sistema, su único efecto sobre el ambiente puede representarse por la elevación de un peso.

!!! warning
    Es importante destacar que se dice *puede*, lo cual no significa que tenga que darse realmente la elevación de un peso. También es destacable que, implícitamente, se está utilizando la definición mecánica de trabajo.

!!! danger
    **Criterio de signos**

    *Bibliografía*

    Suele consider el punto de vista del sistema:

    - positivo: lo que demos al sistema
    - negativo: lo que se extraiga de él (lo produce el sistema)

    *Termodinámica técnica*

    Se encuentra con cierta frecuencia el criterio opuesto para el trabajo: el trabajo es positivo cuando lo produce el sistema y negativo cuando se le suministra.

    Conviene tener claro que cualesquiera de los criterios es adecuado si se utiliza coherentemente. Llevaría a un resultado incorrecto la utilización sucesiva de los dos criterios en el análisis de las distintas partes de un problema.

## Calor

!!! note
    O trabajo irreversible.


!!! note
    El $Q$ y el $W$ son

!!! warning
    $E$ es propiedad, pero $Q$ y $W$ no lo son. Esto se pone de manifiesto al expresarlo en forma diferencial:
    $$
    dE = \delta Q - \delta W \qquad \text{ó} \qquad de = \delta q - \delta w
    $$

!!! danger
    Criterio (o convención) de signos.

En el estudio de la termodinámíca se considerará:

- cómo son afectadas las propiedades de un sistema por la transferencia de energía
- cómo la energía puede transformarse de una forma en otra
- que limítaciones tienen estas transformaciones
- cómo se puede utilizar la capacidad de transformación de la energía en el diseño de máquinas útiles

también veremos que mientras que es posible convertir completamente trabajo en calor la inversa no es cierta.

## Energía interna
La energía interna ($u$) es función del estado del sistema. Por lo que: $u = u (p, T)$, o $u = u (p, v)$ o $u = u(v,T)$.

!!! note
    Para substancias puras, el estado completo del sistema se especifica si cualesquiera dos propiedades son especificadas.

!!! note
    La energía interna ($u$) sale del movimiento aleatorio y desordenado de las moléculas del sistema. Este movimiento depende fundamentalmente de la temperatura, por lo que a veces a la energía interna se le llama *energía térmica*.
