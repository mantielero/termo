# Casos particulares (Corolarios)
### Considerando sólo la energía interna del sistema
Esto es, con las hipótesis:
$$
\begin{align}
&E_c=0 \\
&E_p=0 \\
&E_{química} = 0
\end{align}
$$

se cumplirá:
$$
\begin{align}
\Delta U &= Q - W \\
\Delta u &= q - w \\
dU &= \delta Q - \delta W \\
du &= \delta q - \delta w
\label{eq:sample}
\end{align}
$$

#### Procesos cuasiestáticos (y la única forma de trabajo es por cambio de volumen)
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
Transformación adiabática es aquella en la que sólo intervienen interacciones de trabajo:
$$
Q=0
$$

Cuando el proceso es adiabático, el trabajo ($W$) pasa a depender sólo de los estados inicial y final:
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

#### Sistema aislado
El sistema estará aislado del medio ambiente si el límite de un sistema está formado por:
- paredes adiabáticas rígidas
- sin ejes que las atraviesen

las propiedades que definen el estado del sistema, también denominadas coordenadas termodinámicas del sistema, no se ven afectadas por la presencia de otros sistemas cualesquiera en el entorno del mismo, independientemente de las coordenadas que definieran el estado es estos.

Para poder interaccionar con sistemas rodeados por paredes adiabáticas es preciso que haya algún límite móvil o que un eje o carga eléctrica pueda atravesar la frontera del sistema, dicho de otra forma: es preciso que pueda realizarse trabajo.
