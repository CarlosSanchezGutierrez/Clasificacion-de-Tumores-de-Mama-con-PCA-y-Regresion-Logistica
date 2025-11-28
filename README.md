# Clasificacion-de-Tumores-de-Mama-con-PCA-y-Regresion-Logistica
Este proyecto utiliza técnicas de inteligencia artificial y reducción de dimensionalidad para el análisis de datos sobre el cáncer de mama. A través del Análisis de Componentes Principales (PCA), se reduce la dimensionalidad de los datos, lo que mejora la eficiencia de los modelos predictivos aplicados al conjunto de datos del cáncer.

Los conceptos clave que se abordan son:

PCA (Principal Component Analysis): Se aplica para reducir la dimensionalidad de las características originales del conjunto de datos, concentrando la información relevante en los primeros componentes principales. Esto permite visualizar y trabajar con menos variables sin perder información crítica.

Regresión Logística: Se utiliza como modelo de clasificación para predecir la probabilidad de que un tumor sea maligno o benigno, basándose en las características de los datos (como el radio, textura, área, etc.). Se entrenan modelos de regresión logística tanto con el conjunto completo de características como con el componente principal obtenido de PCA.

Evaluación de Modelos: Se evalúa la precisión de los modelos utilizando diferentes enfoques: con todas las características, con solo el primer componente principal de PCA, y con características individuales, lo que permite comparar el rendimiento de cada enfoque.

Descripción de los Datasets

El dataset utilizado es el Conjunto de Datos sobre Cáncer de Mama. Este conjunto de datos contiene información sobre características computadas de imágenes de tumores mamarios, y está etiquetado con 0 para tumores benignos y 1 para tumores malignos.

Características: El dataset incluye características como radio (promedio de la distancia entre los puntos más cercanos del contorno), textura, perímetro, área, entre otras. Estas características se utilizan para clasificar los tumores.

Diagnóstico: La columna "diagnosis" contiene las etiquetas: B para benigno y M para maligno, que se mapean a valores numéricos (0 y 1, respectivamente).

Este proyecto utiliza el conjunto de datos de cáncer de mama para implementar un análisis de reducción de dimensionalidad y clasificación supervisada. Se aplica PCA (Análisis de Componentes Principales) para reducir las dimensiones del conjunto de datos, lo que mejora la eficiencia computacional y facilita la visualización, concentrando la varianza en los primeros componentes principales.

Se emplea un modelo de regresión logística para clasificar tumores como benignos o malignos. El modelo se entrena utilizando el conjunto completo de características y se evalúa también con solo el primer componente principal obtenido de PCA. Se comparan las precisiones de estos enfoques, lo que permite evaluar la efectividad de la reducción de dimensionalidad en el rendimiento del modelo.

El análisis incluye la comparación del rendimiento de regresión logística utilizando cada característica individualmente, lo que da como resultado un gráfico de barras para visualizar la precisión de cada variable. Este enfoque permite identificar cuáles características son más informativas para la clasificación de los tumores.

A través de este proyecto, se demuestran habilidades en análisis de datos, modelado predictivo, y evaluación de modelos de machine learning en el contexto de la salud, con un enfoque en la optimización de modelos mediante técnicas de reducción de dimensionalidad. Esta experiencia es particularmente valiosa para roles relacionados con ciencia de datos, inteligencia artificial y machine learning, especialmente en aplicaciones médicas.
