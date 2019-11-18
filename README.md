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