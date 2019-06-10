# Postulado de estado
El número de propiedades termodinámicas que definen el estado de un sistema está perfectamente definido y, por lo tanto, no todas las propiedades termodinámicas de un sistema se pueden hacer variar independientemente unas de otras.

!!! note
    **Ejemplo**

    Como ejemplo, que justifica lo que se ha dicho, considerese la conocida ecuación utilizada para gases ideales:

    $$
    p v = R T
    $$

    en la que:

    - $R$: es una constante característica del gas
    - $v$: es el volumen específico másico y la constante universal de los gases en el caso de que v sea el volumen molar.

    Es fácil ver que en esta ecuación sólo dos de las coordenadas de estado del sistema ($p$, $v$, $T$) pueden variar independientemente. Por lo tanto, en el caso de gases ideales, sólo dos propiedades termodinámi­cas definen el estado del sistema y por lo tanto cualesquiera otras propiedades se pueden dar en función de dos de ellas.

Para conocer el número de propiedades termodinámicas que es preciso considerar en el estudio de cualquier sistema termodinámico se dispone de una regla: el denominado *principio* o *postulado de estado*, enunciado por Kline y Koening en 1957.


!!! danger
    Lo siguiente sólo tiene sentido una vez visto el equilibrio

Este postulado no es más que una generalización del hecho, puesto de manifiesto experimentalmente, de que sólo comunicando trabajo reversible o calor a un sistema en equilibrio se puede modificar su estado y que cada una de estas formas de cambiar el estado del sistema está ligada a una variable de estado. En lo que hemos dicho anteriormente está implícitamente  considerada  la  circunstancia  de  que  cualquier  forma  de trabajo  irreversible puede sustituirse por la correspondiente forma de trabajo reversible más transferencia de calor, o sólo calor.

Todo lo dicho se puede resumir en el enunciado de Kline y Koening del postulado de estado:

!!! note
    El número de propiedades termodinámicas independientemente variables, para un sistema determinado, es igual al número de modos de trabajo reversible importantes para el sistema más uno.

Aunque parezca reiterativo, es conveniente destacar algunas de las ideas contenidas en las palabras utilizadas en el enunciado:

- *propiedades termodinámicas*, implica que se hace referencia a características del sistema relacionadas con los estados de equilibrio termodinámico, propiedades tales como color y forma no se consideran.
- *sistema determinado*, hace referencia a una determinada masa de una sustancia especificada.
- *modos de trabajo reversible importantes para el sistema* implica que sólo se consideran modos de trabajo que pueden producir cambios mensurables en la energía del sistema y cuyo valor sea notable en el computo total. También está implícito que, en principio, no se tienen en cuenta las formas de trabajo ineversible.
- *más uno* tiene en cuenta el control independiente de la energía de un sistema mediante el aporte de calor o trabajo irreversible (si sólo equivale a calor).

!!! warning
    El principio de estado establece el número de propiedades independientes, pero no dice que cualesquiera $n+ 1$ propiedades sean un conjunto de propiedades independientes.

    No obstante, para un sistema dado, los *n* desplazamientos generalizados *X* y la energía *E*, siempre constituyen un conjunto de propiedades independientes.

## Sistemas simples
En el estudio termodinámico de sistemas de interés técnico o científico, rara vez se presentará el caso en el que pueda actuarse sobre ellos con más de una forma de trabajo.

Es decir, se verán a lo largo del estudio de la termodinámica sistemas en los que es importante: el trabajo de expansión o compresión, el trabajo elástico, el eléctrico, etc., pero no una combinación de dos o más de ellos.

**Sistemas simples** serán aquellos sobre los que es posible actuar con una sola forma de trabajo.

El estado de equilibrio de una sustancia simple homogénea está determinado cuando se fijan dos propiedades termodinámicas independientes.

Es decir, una vez que el valor de dos propiedades termodinámicas está determinado, el resto de las propiedades tienen valores fijos. También se puede decir que, en una sustancia simple, sólo se pueden variar independientemente dos propiedades termodinámicas

Para caracterizar los distintos sistemas simples se suele hablar de sistemas compresibles simples, sistemas elásticos simples, sistemas magnéticos simples, etc.

### Sistema compresible
Un **sistema compresible** (sistema compresible simple) se define como aquel para el que la única forma de trabajo importante es el trabajo de desplazamiento de la frontera ($-p dV$).

Para tal tipo de sistemas los efectos de tensión superficial (capilaridad), esfuerzo anisótropo y campos de fuerzas externos se desprecian. Esto no quiere decir que el sistema no se vea influido por estos efectos, pero sí que la influencia de los mismos es despreciable frente a $-p dV$.

Conviene usar propiedades intensivas (específicas)

!!! note
    A fin de conseguir ecuaciones que no se limiten a un sistema en particular sino que puedan ser utilizadas en todos los sistemas de la misma clase y centrándonos en los sistema simples compresibles, es conveniente que nos refiramos a las propiedades por unidad de masa del sistema.

!!! note
    **Ejemplo**

    Supóngase que para estudiar un determinado sistema se eligen como variables el volumen y la energía interna, ya que ambas fijan el estado del sistema. Si estas variables se refieren a la unidad de masa del sistema, también definirán su estado termodinámico, por lo que la temperatura, presión y todas las restantes propiedades termodinámicas intensivas serán función únicamente de $u$ y $v$.

    Por lo tanto:
    $$
    T= T(u,v) \\
    p = p(u,v)
    $$

    Este sistema de ecuaciones se podrá resolver  respecto a $u$ y $v$, obteniéndose :

    $$
    u= u(T,p) \\
    v = v(T,p)
    $$

    Por lo que, dados los valores de dos propiedades ($T$ y $p$, por ejemplo) de un sistema simple compresible (en cualquier otro sistema simple serían otras propiedades caracteristicas del mismo) se puede, en principio, determinar los valores de $u$ y $v$ y por lo tanto el estado del sistema.

    Por lo tanto, se puede inferir que dos propiedades termodinámicas independientes cualesquiera de un sistema homogéneo compresible simple definen el estado del mismo.

!!! note
    Téngase en cuenta que la forma que toman estas relaciones no la proporciona la termodinámica. Estas relaciones pueden obtenerse o experimentalmente, o mediante la teoría cinético-molecular y la fisica estadística.

    No obstante, desde el punto de vista de la termodinámica lo importante es que estas relaciones existen y que puede recurrir a ellas cuando las necesita.
