# Propiedades
## ¿Qué es una propiedad?
Llamamos **propiedades** (o *Propiedades termodinámicas de un sistema* o *variables termodinámicas* o *variables de estado*) a cualesquiera características macroscópicas observables. Por ejemplo: la masa, el volumen, la presión, la temperatura..., cuyos valores numéricos pueden asignarse en un momento dado sin tener en cuenta la historia del sistema.

## Directamente/Indirectamente observables
Será también propiedad del sistema a cualquier relación entre las propiedades directamente observables del mismo (ej. producto de la presión y el volumen; producto de la presión y la temperatura, etc). Tales propiedades pueden considerarse *caracterí­sticas indirectamente observables* de un sistema.

Teóricamente pueden definirse un gran número de propiedades, pero como se verá, sólo unas pocas resultan útiles.

Hay otro tipo de propiedades de un sistema que no son directamente observables y que se deducen de los principios de la termodinámica. En las lecciones correspondientes se verá cómo se introducen la energí­a interna, la entalpí­a, la entropí­a, etc., a partir de estos principios.

## No propiedades
En el estudio de la termodinámica también se encuentran magnitudes que no son propiedades, porque sus valores dependen de la trayectoria seguida por el sistema, pudiendo citar entre ellas las transferencias de energí­a, como son el calor y el trabajo.

No son propiedades ni el calor, ni el trabajo pues no es algo que sea propio del sistema, sino que se trata de transferencias energéticas.

## Matemáticamente hablando
Sean:

* $x_1, ..., x_n$: propiedades de un sistema que lo caracterizan (variables de estado).
* $y=y(x_1, ..., x_n)$: $y$ es una nueva propiedad (función de estado). Es una relación entre las propiedades anteriores.

Diremos que $y$ es propiedad si y sólo si $y$ es diferencial exacta. Esto es, cumple:

1. $y$ es diferenciable:

$$
dy = \sum \frac{\partial y }{\partial x_i} dx_i
$$

2. $y$ verifica Schwarz (igualdad de derivadas cruzadas):

$$
\frac{\partial^2y}{\partial x_i \partial x_j} = \frac{\partial^2y}{\partial x_j \partial x_i}
$$

Si $y$ no fuese una propiedad no cumplirí­a (1) y/o (2).

### Cambios diferenciales
Si $y$ no es propiedad, representaremos un cambio diferencial mediante el símbolo $\partial y$, que podrá expresarse:
$$
\partial y = \sum z_i dx_i
$$

donde $z_i$ y $x_i$ son variables de estado para las que:

$$
\frac{\partial z_i}{\partial x_i} \neq \frac{\partial z_j}{\partial x_i} \Rightarrow \partial y \quad \text{no es diferencial exacta}
$$

La integral de $y$ dependerá de la trayectoria (integral de lí­nea).

!!! note
    Observar que:

    - $dy$: indica que $y$ es propiedad
    - $\partial y$: indicamos que $y$ **no** es propiedad.


## Propiedades extensivas, intensivas y especí­ficas
Las propiedades termodinámicas pueden dividirse en dos grandes grupos:

* **Propiedad extensiva**: si su valor para el sistema en conjunto es la suma del valor correspondiente a cada parte en las que el sistema puede dividirse. Entre ellas se pueden citar la masa y el volumen, así­ como muchas otras que irán apareciendo.
* **Propiedades intensivas**: son aquellas que tienen el mismo valor para cualquier parte del sistema homogéneo que para el sistema en conjunto. La presión, temperatura y densidad son ejemplos de estas propiedades.

!!! note
    Las propiedades extensivas suelen representarse con letras mayúsculas.
    Las intensivas con letras minúsculas.
    Como excepción:

    - $T$: temperatura termodinámica del sistema es intensiva
    - $m$: la masa del sistema es extensiva

Si el valor de una propiedad extensiva se divide entre la masa del sistema, la propiedad resultante es una propiedad intensiva y se denomina **propiedad especí­fica**. Se representará consecuentemente con letra minúscula.

!!! note
    El volumen especí­fico se obtiene dividiendo el volumen total del sistema (propiedad extensiva) entre la masa del mismo. Esta relación del volumen a la masa es la misma para cualquier punto de un sistema homogéneo y por tanto es una magnitud intensiva.



### Matemáticamente
Se puede formular todo lo dicho recurriendo al concepto de *función homogénea*.

!!! note
    Como se recordará o puede verse en cualquier libro de análisis matemático, una función *Y* se denomina homogénea de grado $\alpha$ cuando se verifica:
    $$
    Y(\lambda X_1, \lambda X_2, ..., \lambda X_n) = \lambda^\alpha Y(X_1, X_2, ..., X_n)
    $$

    en la que las $X_i$ son propiedades extensivas del sistema.

Para las funciones homogéneas se cumple el *teorema de Euler*:
$$
\sum X_i \frac{\partial Y}{\partial X_i} = \alpha Y
$$

También se verifica que si una función es homogénea de grado $\alpha$  su derivada de orden $p$ es homogénea de grado $\alpha -p$. En esta expresión *p* es un entero positivo, pero $\alpha$ no necesita ser un entero mayor que *p*.

Según lo que acaba de verse, si $Y$ es una propiedad de un sistema simple que contiene $n$ moles de sustancia, $Y$ será intensiva o extensiva según sea proporcional a $n^0$ o a $n^1$. Es decir:

$$
\begin{align}
\alpha = 0 &\Rightarrow Y \propto n^0 &\Rightarrow \text{intensiva}\\
\alpha = 1 &\Rightarrow y \propto n^1 &\Rightarrow \text{extensiva}
\end{align}
$$

!!! note
    Así:

    - $V$: (volumen total) es extensiva, ya que si se duplica el número de moles del sistema, conservando constantes todos los parámetros intensivos, el volumen se duplica.
    - $v = \frac{V}{n}$: (volumen especí­fico molar) será intensiva. Resulta de dividir el volumen total entre el número de moles del sistema.

!!! warning
    Conviene tener claro que cualquier propiedad extensiva $Y$ tiene una variable intensiva correspondiente $\frac{Y}{n}$, pero la inversa no es siempre cierta ya que variables como $T$ y $p$ no poseen sus correspondientes extensivas.

### Ejemplo
#### $Y$ extensiva
Supóngase que $Y$ es una propiedad extensiva dependiente de otras propiedades extensivas $X_i$. El requisito de que $Y$ sea una propiedad extensiva significa que si se duplican las $X_i$, se duplica $Y$, es decir:

$$
Y( 2X_1, 2X_2, ..., 2X_n) = 2 Y(X_1, ..., X_n)
$$

y en general:

$$
Y(\lambda X_1,\lambda X_2, ..., \lambda X_n) = \lambda Y(X_1, ..., X_n)
$$

en otras palabras, $Y$ es homogénea de grado uno.

#### $Y$ intensiva
Considerando que $Y$ sea una propiedad intensiva, al duplicar las $X$ se deja sin alterar la $Y$, o en general:

$$
Y(\lambda X_1,\lambda X_2, ..., \lambda X_n) = Y(X_1, ..., X_n)
$$

por lo que $Y$ es homogénea de grado cero.

#### Resumiendo
Si $Y$ es una propiedad que depende de variables extensivas $X_i$, resultará que $Y$ será una propiedad:

- *extensiva* si es homogénea de grado uno
- *intensiva* si es homogénea de grado cero.

!!! note
    Según se vió antes al considerar la derivada de orden $p$ de una función homogénea, si $Y$ es extensiva, la primera derivada respecto a una variable extensiva será una propiedad intensiva.
