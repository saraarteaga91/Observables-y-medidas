# Observables y medidas
Esta tarea explora conceptos de la teoría cuántica, basándose en cómo se comportan los sistemas cuánticos bajo medidas y transiciones. 
# Amplitud de transición
Para el cálculo de transición entre dos estados, se usó el producto interno, con la función np.dot() de Numpy.
# Media y varianza
Al hallar que la matriz es hermitiana, se calcula la media y la varianza de un observable en algún estado, usando np.allclose()  no.vdot().
# Autoestados y colapso cuántico
También, se calcularon los autoestados y autovalores de un observable, usando esta información para determinar las probabilidades de colapso del sistema hacia cada autoestado, usando np.linalg.eigh().
# Evolución temporal
Se usó una serie de matrices unitaria con np.dot() para simular cómo evoluciona un estado cuántico con el tiempo.

# Ejercicios resueltos
# 4.3.1: 
Calculo de probabilidades tras aplicar el operador Sx usando productos internos con NumPy.
# 4.3.2:
Gráfica de probabilidades de transición usando Matplotlib.
# 4.5.2:
Creación del estado entrelazado de Bell mediante productos tensoriales con np.kron().
