# Primer principio aplicado a *Sistemas Cerrados*
La aplicación del primer principio a un *sistema cerrado* conduce a las expresiones:

- Proceso elemental:
$$
\delta Q + \delta W = dE
$$
- Proceso finito:
$$
Q_{12} + W_{12} = \Delta E
$$

Usando magnitudes específicas (por unidad de masa):
$$
\partial q + \partial w = de \\
q_{12} + w_{12} = \Delta e
$$

## Sistemas cerrados simples (compresibles)
Consideremos únicamete la posibilidad de trabajo reversible y para el caso de que se considere un sistema compresible simple:
$$
\delta w = -p dv \\
w_{12} = \int_1^2 -pdv
$$

## Si sólo importa la energía interna ($u$)
Si además se supone que la única forma de energía importante es la variación de energía interna, $u$, las expresiones anteriores tomarán la forma:

$$
\delta q - pdv = du \\
q_{12} - \int_1^2 pdv = \Delta u
$$

Por la frecuencia con que se presentan, aplicamos estas ecuaciones a procesos que se realizan a volumen constante y a presión constante.

### Procesos a volumen constante (isócoros)
Si el proceso se realiza a **volumen constante** (isocoro):

$$
\require{cancel}
\delta q_v - p\cancelto{0}{dv} = d u_v
$$


Por ser $u$ una propiedad termodinámica de un *sistema compresible simple* se podrá expresar en función de dos variables termodinámicas del mismo. Se suelen escoger $T$ y $v$ como variables adecuadas para expresar esta función, por lo que:


$$
\require{cancel}
du_v = \left( \frac{\partial u}{\partial T} \right)_v dT +  \left( \frac{\partial u}{\partial v} \right)_T \cancelto{0}{dv} = \left( \frac{\partial u}{\partial T} \right)_v dT_v
$$

Se define el **calor específico a volumen constante** como:
$$
c_v =  \left( \frac{\partial u}{\partial T} \right)_v \qquad \left[\frac{kJ}{kg \cdot K}\right] \text{ ó } \left[\frac{kJ}{kmol \cdot K}\right]
$$
(según se refiera a la unidad de masa o a la unidad de sustancia)

Consecuentemente, la ecuación del primer principio quedará:
$$
\require{cancel}
\partial q_v - p\cancelto{0}{dv} = \cancelto{c_v dT}{d u_v} \Longrightarrow c_v dT = \partial q_v
$$

que nos permite expresar $c_v$ mediante:
$$
c_v = \frac{\partial q_v}{dT}
$$


!!! note
    Esta forma de expresar $c_v$ sirve de base a la determinación calorimétrica de $c_v$. Para realizar esta determinación experimental se mide la cantidad de calor transferida a volumen constante a un determinado sistema, $q_{12(v)}$,  necesaria para conseguir un incremento de temperatura  $\Delta T_v$:

    $$
    c_v = \frac{q_{12(v)}}{\Delta T_v}
    $$


Teniendo en cuenta la posibilidad  de determinar $c_v$, se puede dar una expresión de $du$, para un **sistema compresible simple**, mediante la expresión:

$$
du_v = c_v dT +  \left( \frac{\partial u}{\partial v} \right)_T dv
$$


### Procesos a presión constante (isóbaros)
Para un sistema que experimenta una transformación a presión constante:
$$
\partial q_p -p dv_p = du_p \longrightarrow \partial q_p = p dv_p + du_p = d(u+pv)_p
$$

Llamaremos **entalpía** ($h$) al conjunto de propiedades ($u + pv$).

$$
H \equiv U + pV\\
h \equiv u + pv
$$

La entalpía es una propiedad termodinámica (por ser combinación de propiedades termodinámicas).

Para un sistema simple podrá expresarse en función de dos propiedades termodinámicas cualesquiera. Para *sistemas simples compresibles* es frecuente escoger $T$ y $p$, por lo que para $h(T,p)$ se cumplirá:

$$
dh = \left( \frac{\partial h}{\partial T} \right)_p dT + \left( \frac{\partial h}{\partial p} \right)_T dp
$$

se define el **calor específico a presión constante** como:

$$
c_p = \left( \frac{\partial h}{\partial T} \right)_p
$$

Luego:
$$
dh = c_p dT + \left( \frac{\partial h}{\partial p} \right)_T dp
$$

Para una transformación a **$p$ constante**:

$$
\require{cancel}
dh_p = c_p dT + \left( \frac{\partial h}{\partial p} \right)_T \cancelto{0}{dp} = c_p dT
$$

Luego la ecuación del primer principio para un sistema compresible simple que sufre una transformación a presión constante quedará:

$$
\partial q_p = d(u+pv)_p = dh_p = c_p dT
$$

Por lo que se puede expresar $c_p$ mediante:
$$
c_p = \frac{\partial q_p}{dT}
$$

que proporciona un posible método experimental de determinación de $c_p$ midiendo el calor transferido a presión constante a un sistema y el correspondiente  incremento de $T$.

En general:

$$
q_{p(1,2)} = \int_1^2 c_p dT
$$

!!! note
    La integración del segundo miembro es, en general, fácil de hacer, aunque con frecuencia haya que recurrir a métodos gráficos o numéricos.

$c_p$ y $c_v$ comparten unidades.

Conviene destacar que, tanto en el caso de una transformación a volumen constante como a presión constante, el calor transferido en el proceso es posible darlo como diferencia del valor de propiedades termodinámicas del sistema correspondientes a los estados extremos (*u* y *h* respectivamente), es decir:

$$
q_{v(1,2)} = u_2 - u_1 \\
q_{p(1,2)} = h_2 - h_1
$$

!!! danger
    ¿Son $c_p$ y $c_v$ propiedades del sistema? No. Es decir, sus valores no determinan el estado del sistema.

    Son características de la substancia de trabajo:

    $c_V$: es la cantidad de calor que es necesario suministrar a un mol de gas ideal para elevar su temperatura un grado mediante una transformación isócora.

    $c_p$: es la cantidad de calor que es necesario suministrar a un mol de gas ideal para elevar su temperatura un grado mediante una transformación isóbara.


### Aportación de trabajo irreversible
Consideremos ahora qué ocurre cuando, además de trabajo	reversible hay una aportación de trabajo irreversible al sistema, como podría ser la agitación mediante paletas, aporte de carga eléctrica a través de una resistencia eléctrica, etc.

La ecuación del primer principio para un sistema compresible simple, para transformaciones a:

- volumen constante:
$$
\require{cancel}
\delta q_v + \delta w_{irre} -p \cdot \cancelto{0}{dv} = du_v
$$

- presión constante:
$$
\delta q_p + \delta w_{irre} -p \cdot dv = du_p \longrightarrow \delta q_p + \delta w_{irre} = dh_p
$$

Para un proceso finito tendríamos:

- volumen constante:
$$
q_{v(1,2)} + w_{irre} = \Delta u_v
$$

- presión constante:
$$
q_{p(1,2)} + w_{irre} = \Delta h_p
$$

Vemos que, para un  determinado cambio de estado, independientemente de que la transformación en conjunto sea reversible o no lo sea, tanto la variación de $h$ como la de $u$ estarán perfectamente definidas, por lo que conociendo alguno de los otros dos datos, es posible determinar el tercero.
