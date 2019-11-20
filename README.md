# Machine Learning
✏️ Apuntes y conceptos básicos del🤖Machine Learning 🔥🐉 - ¡Que debes saber!

## Temario 📘 

- **Entornos** (Instalación de Anaconda, Jupyter Notebook Online) 

- [**Curso básico de Python**](./BasicPython) (Números, cadenas, listas, diccionarios, tuplas, conjuntos, operaciones, función range, map, filter, bucles, for y while, y funciones lambda) 

- [**Módulo Numpy**](./NumPy) (Numpy con listas, funciones arange, ones, zeros, linspace, números aleatorios y arrays de 1 y 2 dimensiones) 

- [**Módulo Pandas**](./Pandas) (Series, Data Frames, selección de datos, modificación de filas, tratar valores nulos, agrupación por columnas, combinar Data Frames, Merge y Join en Data Frames, leer ficheros tipo excel, leer páginas web HTTML, grabar Data Frames, en tablas SQL y gráficos con pandas) 

- [**Módulo Matplotlib**](./Matplotlib) (gráficos, multigráficos, tamaño del gráfico, crear 2 gráficos en la misma figura, color del gráfico, tipo de línea y marcadores)

- **Scikit Learn** es el paquete de machine learning más popular y tiene muchos algoritmos pre-construidos. Incluye varios algoritmos de _clasificación_, _regresión_ y _análisis de grupos_ entre los cuales están _máquinas de vectores de soporte_, _bosques aleatorios_, _Gradient boosting_, _K-means_ y _DBSCAN_. Está diseñada para interoperar con las bibliotecas numéricas y científicas _NumPy_ y _SciPy_. Se install `pip install scikit-learn` y en conda `conda install -c anaconda scikit-learn`.

## ¿Qué es el Marchine Learning?

- Machine learning o aprendizaje de máquinas o aprendizaje automático, es el subcampo de las ciencias de la computación y una rama de la inteligencia artificial, cuyo objetivo es desarrollar técnicas que permitan que las computadoras aprendan.

- Machine learning es un método de análisis de datos que automatiza la contrucción de un modelo analítico.

- Machine learning permite a los ordenadores encontrar soluciones a problemas, sin ser explíitamente programados para ello, gracias al uso de algoritmos, que aprenden de los datos.

### Procesos de Machine Learning

!["Procesos de Machine Learning url:.images/Proceso_ML_ZONE.png"](.images/Proceso_ML_ZONE.png)

### Tipos de algoritmos de Machine Learning

- **Aprendizaje supervizado**: Este algoritmo necesita datos previamente etiquetados (solucinados) para aprender a realizar el trabajo. En base a estos datos, el algoritmo es capaz de aprender a resolver problemas futuros similares.

- **Aprendizaje no supervizado**: Este algoritmo necesita indicaciones previas, que le enseñan a comprender y analizar la información, para resolver problemas futuros similares. No necesita datos previamente etiquetados.

- **Aprendizaje de refuerzo**: Este algoritmo aprende por su cuenta, en base de unos conocimientos previamente introducidos y a la práctica que realiza sobre los problemas aprendiendo en función del éxito o fracaso que obtiene al resolver los problemas.

### Algoritmos de Machine Learning 🐍📊

- [**Regresión Lineal**](./RegresionLineal) es una aproximación para modelar la relación entre una varible escalar dependiente "y" y una o más variables explicativas "x".

- [**Regresión Logística**](./RegresionLogistica) es un tipo de análisis de regresión, utilizado para predecir el resultado de una variable categórica (una variable que puede adoptar un númerolimitado de categorías) en función de otras variables independientes.

- [**k vecinos más próximos - KNN**](./KNN) en el reconocimiento de patrones, este algoritmo es usado como método de clasificación de objetos, basado en un entrenamiento mediante ejemplos cercanos en el espacio de los elementos.

- [**Arboles de Decisión**](./ArbolesDeDecision) dado un conjunto de datos, se fabrican diagramas de contrucciones lógicas, que sirven para representar y categorizar una serie de condiciones que ocurren de forma sucesiva, para la resolución de problema.

- [**Bosques Aleatorios - Random Forest**](./BosquesAleatorios) es una combinación de árboles de decisión, donde cada árbol selecciona una clase y luego se combinan las decisiones de cada árbol, para seleccionar una clase final ganadora.

- [**Máquinas de Vectores de Soporte  - Support Vector Machine - SVM**](./SVM) representa los puntos de muestra en el espacio, separando las clases en dos espacios lo más amplio posible mediante un hiperplano de separación, denominado vector de soporte.

- [**Algoritmo de K-Medias**](./K-Medias) tiene como objetivo la partición de un conjunto de 'n' objetivos en 'k' grupos, en el cada observación pertenece al grupo cuyo valor medio es más cercano.

## Deep Learning 🧠🌋

### Redes Neuronales

_Marco teórico, y representación analógica de las redes reuronales._

#### (_Neurona y Perceptrón_)

- Una neurona es una célula y el componente principal del sistema nervioso, cuya función principal es recibir, precesar y transmitir información a través de señales químicas y eléctricas.

- Se dividen en tres partes principales:
    - **Soma**: cuerpo celular o núcle.
    - **Dentritas**: Prolongaciones cortas que reciben información y la transmiten al Soma.
    - **Axón**: Prolongación corta que conduce los impulsos hacia otra neurona.

!["Una Neurona url:.images/una_neurona.gif"](.images/una_neurona.gif)
<!-- !["Neurona url:.images/una_neurona.gif"](.images/neurona.png) -->

#### Perceptrón

- Un perceptrón es una neurona artificial.
- Se une con otros perceptrones para crear una red neuranol artifical.
- Cada perceptrón tiene:
    - Canales de entrada (x1, x2, .. xn) (Dentritas)
    - Función de activación (Soma o núcle)
    - Canal de salida (y) (Axón)

!["Perceptron_5_unidades url:.images/Perceptron_5_unidades.png"](.images/Perceptron_5_unidades.png)

- Su representación matemática es:

!["Representación Matemática url:.images/repre_mat.png"](.images/repre_mat.png)

### Redes Neuronales Artificiales

- Una red reuronal artificial consiste en un conjunto de reuronas artificiales (perceptrones) conectadas entre sí para transmitirse señales.
- La información de entrada atraviesa la red neuronal (donde se somete a diversas operaciones).
- Cada neurona aritificial está conectada con otras neuronas a través de unos enlaces. En estos enlaces, el valor de salida de la neurona es multiplicado por un valor (peso de enlace).
- A la salida de la neurona, está la función de activación que modifica el valor del resultado de esa neurona, que posteriormente debe enviarse a la siguiente neurona.

### Función de Activación

- Funciones de activación de una neurona actificial **sirve para definir el valor de salida en función de los datos de entrada**.
- La función de activación se encarga de devolver una salida a partir de un valor de entrada, normalmente el conjunto de valores de salida en un rango determinado como (0,1) o (-1,1).
- Existen diferentes tipos de funciones de activación:
    - **Sigmoide**: La función sigmoide transforma los valores introducidos a una escala (0,1), donde los valores altos tienen de manera asintótica a 1 y los valores muy bajos tienden de manera asintótica a 0.
    - **Tanh - Tangente hiperbólica**: La función tangente hiperbólica transforma los valores introducidos a una escala (-1,1), donde los valores altos tienen de manera asintótica a 1 y los valores muy bajos tienden de manera asintótica a -1.
    - **ReLU - Unidad lineal rectificada**: La función ReLU transforma los valores introducidos anulando los valores negativos y dejando los positivos tal y como entran.
    - **Leaky ReLU - Unidad lineal rectificada**: La función Leaky ReLU transforma los valores introducidos multiplicando los negativos por un coeficiente rectificativo y dejando los positivos según entran.
    - **Softmax – Unidad lineal rectificada**: La función Softmax transforma las salidas a una representación en forma de probabilidades, de tal manera que el sumatorio de todas las probabilidades de las salidas de 1.