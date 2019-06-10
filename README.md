# Limpieza_y_validacion_PR2_UOC

## Autores: Gabriel Peso Bañuelos, Jon Ortiz Abalia

## Descripción

Práctica 2 (Limpieza y validación de datos) enmarcada dentro de la asignatura "Tipología y ciclo de vida de los datos" (Máster de Ciencia de Datos, UOC, 2019). Para la práctica hemos utilizado un conjunto de datos disponible en una competición de *Kaggle* (https://www.kaggle.com/c/tmdb-box-office-prediction) en la que se incluye un dataset con 3000 películas de las que hay que predecir su recaudación a partir de múltiples variables numéricas y categóricas que incluyen presupuesto, duración, idioma, reparto, fecha de estreno etc.

## Ficheros

- **PRA2_Tipologia.rmd**: código del proyecto en fomrato R Markdown.
- **train.csv**: fichero csv con los datos originales obtenidos a partir de *Kaggle*
- **trainout.csv**: fichero csv con los datos limpios y transformados
- **PRA2_Tipologia.pdf**: documento pdf del proyecto incluyendo las respuestas a las preguntas planteadas en el enunciado

## Consideraciones

* El objetivo del proyecto ha sido generar un modelo de regresión linear múltiple para predecir el valor de la variable *revenue* a partir de una serie de variables explicativas seleccionadas de entre las 23 variables originales. A tal efecto se ha utilizado exclusivamente el archivo *train.csv*. No se ha utilizado el otro archivo *test.csv* para realizar la predicción de casos nuevos por considerar que excedía del contexto del presente trabajo.

## Recursos

* Subirats, L., Calvo, M. (2018). **Web Introducción a la limpieza y análisis de los datos**. Editorial UOC.
* Squire, M. (2015). **Clean Data**. Packt Publishing Ltd.
* Dalgaard, P. (2008). **Introductory statistics with R**. Springer Science & Business Media.
* Frost, J. (2019). **Regression analysis: an ultimate guide**

