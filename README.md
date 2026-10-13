## Analisis de sensibilidad de un modelo de un cantilever beam piezoeléctrico

Este programa implementa un modelo lineal acoplado de un cosechador de energía piezoeléctrico en configuración de cantilever, representado mediante un sistema de un grado de libertad (1 dof) y sometido a una excitación armónica de base.

El código analiza la respuesta dinámica del sistema en función de la frecuencia, calculando el desplazamiento mecánico, el voltaje generado y la potencia eléctrica promedio entregada a laa resistencia de carga.

Además, realiza un análisis de sensibilidad paramétrica mediante diferencias centrales para evaluar la influencia de la masa modal, la frecuencia natural, el amortiguamiento, el acoplamiento piezoeléctrico, la capacitancia, la resistencia de carga y la aceleración de excitación. Finalmente, estudia el efecto de la resistencia de carga sobre la potencia máxima obtenida, permitiendo identificar su valor óptimo dentro del intervalo analizado.

Requisitos.
Matlab 16 o superior.
