# Data Augmentation via Warping Transforms for Modeling Natural Variability in the Corneal Endothelium Enhances Semi-Supervised Segmentation

El aprendizaje profundo ha aportado una contribución muy significativa a la segmentación de imágenes biomédicas, automatizando el proceso de delimitación en las imágenes médicas. Para realizar dicha tarea, los modelos deben entrenarse utilizando una gran cantidad de datos anotados o etiquetados que resaltan la región de interés con una máscara binaria. Sin embargo, la generación eficiente de anotaciones para datos tan grandes requiere un analista biomédico experto y un gran esfuerzo manual. Es una tarea tediosa y costosa, además de vulnerable a errores humanos. Para abordar este problema, se propone un marco de aprendizaje semisupervisado que se puede entrenar con un número limitado de muestras anotadas y, al mismo tiempo, con una gran cantidad de muestras sin anotaciones, lo que ocurre principalmente en problemas del mundo real.

Este repositorio incluye la implementación del artículo "Data Augmentation via Warping Transforms for Modeling Natural Variability in the Corneal Endothelium Enhances Semi-Supervised Segmentation" que se puede integrar fácilmente con cualquier modelo Encoder-decoder.

## Funcionalidades

El código de esta investigación ofrece las siguientes funcionalidades:

1.	Extraer la parte del codificador y convertirla en Siamese-Net para realizar un entrenamiento previo con Barlow Twins.
2.	Integración del codificador previamente entrenado con el modelo encoder-decoder para realizar ajustes.
3.	Evaluación con métricas estándar para tareas de segmentacion.
4.	Visualización de salida.
5.	También se incluye un jupyter notebook utilizando las diferentes estrategias de aumentación de datos.

## Requisitos

- Python 3.x
- Bibliotecas necesarias:
  - numpy
  - matplotlib
  - scikit-image
  - opencv-python
  - tensorflow / pytorch (dependiendo de la implementación del modelo)
