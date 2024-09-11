# juega-con-una-red-neuronal-
Atrapa Atrapa el Panqueque
Descripción:

"Atrapa Atrapa el Panqueque" es un juego interactivo en HTML y JavaScript en el que los jugadores deben hacer clic en figuras de colores que caen desde la parte superior de la pantalla para ganar puntos. Cada figura representa un "caramelo" con diferentes formas y colores. A medida que el jugador avanza, la dificultad del juego aumenta gradualmente, con niveles que se desbloquean cada 100 puntos.

Características:

Figuras Diversas: Las figuras pueden ser círculos, cuadrados, triángulos, hexágonos, estrellas, diamantes, pentágonos y octágonos, cada una con diferentes colores y tamaños.
Incremento de Dificultad: El juego se vuelve más desafiante a medida que el jugador avanza, con un aumento gradual en la velocidad y número de figuras.
Interactividad: El juego utiliza TensorFlow.js para ajustar dinámicamente la dificultad basada en el desempeño del jugador.
Interfaz de Usuario: Incluye un menú de inicio, instrucciones y un botón para salir del juego.
Instrucciones:

Presiona el botón "Iniciar Juego" para comenzar.
Haz clic en las figuras que caen para acumular puntos.
El nivel aumentará cada 100 puntos, haciendo que el juego sea más desafiante.
Tecnologías Utilizadas:

HTML5
CSS3
JavaScript
TensorFlow.js



Tipo de Red Neuronal
Red Neuronal Densa (Feedforward Neural Network)

Esta red neuronal se clasifica como una red neuronal densa (o feedforward), lo que significa que es un tipo de red neuronal en la que la información se mueve en una sola dirección: desde las neuronas de la capa de entrada a través de las capas ocultas hasta las neuronas de la capa de salida, sin retroalimentación.

Configuración de la Red Neuronal
Capas:

Primera Capa Oculta:

Unidades: 10
Activación: ReLU (Rectified Linear Unit)
Esta capa toma las entradas y aplica la función de activación ReLU, que introduce no linealidad y ayuda a la red a aprender patrones complejos.
Segunda Capa Oculta:

Unidades: 10
Activación: ReLU
Similar a la primera capa oculta, esta capa agrega más capacidad de aprendizaje y complejidad al modelo.
Capa de Salida:

Unidades: 1
Activación: Lineal
La capa de salida produce un solo valor continuo, que en este caso es la predicción de la red. La activación lineal es adecuada para problemas de regresión.
Compilación del Modelo:

Optimizador: Adam
Adam es un optimizador popular que ajusta los pesos de la red neuronal durante el entrenamiento para minimizar la función de pérdida.
Función de Pérdida: Mean Squared Error (MSE)
MSE mide la diferencia cuadrada entre las predicciones del modelo y los valores reales, y es comúnmente usada para problemas de regresión.
