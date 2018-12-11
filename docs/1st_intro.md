# Primera ley de la termodinámica
Para todo sistema existe una propiedad llamada *energía*, $E$ que es suma de:

- energía interna ($u$)
- energía cinética (se ve en física)
- energía potencial (se ve en física)
- energía química (casi nunca se tiene en cuenta).

$$
E = U +  E_{cinética} + E_{potencial} + ...
$$

El cambio de energía de un sistema es igual a la diferencia entre el calor añadido al sistema y el trabajo realizado por el sistema:
$$
\Delta E = Q-W \qquad \text{[J]}
$$
en donde:

- $E$: energía del sistema
- $Q$: calor que entra al sistema
- $W$: trabajo realizado por el sistema

!!! note
    Esto es fruto de la observación.

!!! note
    La *ley cero* definía la propiedad: *temperatura*. La primera ley define una nueva propiedad: *energía*.

!!! note
    Si lo expresamos por unidad másica:
    $$
    \Delta e = q- w \qquad \left[\frac{J}{kg}\right]
    $$


!!! warning
    $E$ es propiedad, pero $Q$ y $W$ no lo son. Esto se pone de manifiesto al expresarlo en forma diferencial:
    $$
    dE = \delta Q - \delta W \qquad \text{ó} \qquad de = \delta q - \delta w
    $$

!!! danger
    Criterio (o convención) de signos.

## Energía interna
La energía interna ($u$) es función del estado del sistema. Por lo que: $u = u (p, T)$, o $u = u (p, v)$ or $u = u(v,T)$.

!!! note
    Para substancias puras, el estado completo del sistema se especifica si cualesquiera dos propiedades son especificadas.

!!! note
    La energía interna ($u$) sale del movimiento aleatorio y desordenado de las moléculas del sistema. Este movimiento depende fundamentalmente de la temperatura, por lo que a veces a la energía interna se le llama *energía térmica*.

## Casos particulares (Corolarios)
### $E_c=0$ y $E_p=0$ (y despreciando energía química)
En este caso:
$$
\begin{align}
\Delta U &= Q - W \\
\Delta u &= q - w \\
dU &= \delta Q - \delta W \\
du &= \delta q - \delta w
\label{eq:sample}
\end{align}
$$

#### Procesos cuasiestáticos
Si además el proceso es cuasiestático: $W = p_{sis}dV$ y consecuentemente:
$$
\begin{align}
dU &= \delta Q - pdV \\
du &= \delta q - pdv
\end{align}
$$

!!! Ejemplo
    Si aplicamos calor a una masa de control y dejamos que se atempere, el volumen que ocupa aumentará. Esto se debe a que al aplicar calor ($Q$), si dejamos que se atempere ($dU=0$), el termino $pdV$ será positivo (por lo que el volumen ocupado aumenta).

#### Proceso adiabático ($Q=0$)
Cuando el proceso es adiabático ($Q=0$), el trabajo ($W$) pasa a depender sólo de los estados inicial y final:
$$
\require{cancel}
\Delta U = \cancelto{0}{Q} - W
$$

#### Proceso cíclico
Como el estado inicial y final serán el mismo:
$$
\require{cancel}
\cancelto{0}{\Delta U} = Q - W \rightarrow Q=W
$$
y consecuentemente:
$$
\oint \delta Q = \oint \delta W
$$
