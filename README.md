# Análisis de Indicadores de Desarrollo

Este repositorio contiene el código desarrollado para el curso de posgrado "INTRODUCCIÓN A CIENCIA DE DATOS Y CÁLCULO AVANZADO", orientado a la aplicación de técnicas de análisis y ciencia de datos mediante Python.

El trabajo utiliza el conjunto de datos *Global Development Analysis (2000–2020)* y analiza indicadores económicos, sociales, digitales y de infraestructura con el propósito de responder dos preguntas principales:

- ¿Es posible predecir el PIB per cápita de un país a partir de sus múltiples indicadores?
- ¿Hay perfiles de paises que sean similares, teniendo indicadores diferentes?

Para abordar estas preguntas se aplicaron técnicas de análisis exploratorio de datos, regresión lineal múltiple, *clustering* mediante K-Means y análisis de componentes principales (PCA).

---

## Contenido del repositorio

- **Análisis exploratorio de datos:** exploración de la distribución y evolución del PIB per cápita y de las relaciones entre los indicadores seleccionados.
- **Regresión lineal:** construcción y evaluación de un modelo para estimar el PIB per cápita a partir de indicadores económicos, sociales, digitales y de infraestructura.
- **Análisis de multicolinealidad:** evaluación de las relaciones entre las variables predictoras mediante el Factor de Inflación de la Varianza (VIF).
- **K-Means:** identificación de perfiles con características similares a partir de los indicadores seleccionados.
- **Selección de clusters:** evaluación de la cantidad de grupos mediante el método del codo y el *Silhouette Score*.
- **PCA:** representación bidimensional e interpretación de los perfiles obtenidos mediante K-Means.

---

## Librerías utilizadas

Los análisis fueron desarrollados en Python utilizando principalmente:

- [`pandas`](https://pandas.pydata.org/) → manipulación y análisis de datos.
- [`numpy`](https://numpy.org/) → operaciones numéricas.
- [`matplotlib`](https://matplotlib.org/) → visualización de datos.
- [`seaborn`](https://seaborn.pydata.org/) → visualización estadística.
- [`scikit-learn`](https://scikit-learn.org/) → regresión, K-Means, PCA, escalado y métricas de evaluación.
- [`statsmodels`](https://www.statsmodels.org/) → análisis estadístico y cálculo del VIF.

---

## Conjunto de datos

Se utilizó el conjunto de datos **Global Development Analysis (2000–2020)**, disponible en Kaggle:

[Global Development Indicators 2000–2020](https://www.kaggle.com/datasets/michaelmatta0/global-development-indicators-2000-2020)

El conjunto reúne indicadores de desarrollo correspondientes al período 2000–2020 e incluye variables económicas, sociales, digitales y de infraestructura.

---

El código utilizado para este trabajo fue brindado por la docente responsable del curso de posgrado. Los cambios que existen se deben a modificaciones propias para el análisis correspondiente o pequeñas lineas de código agregadas para la interpretación de resultados.

---


## Autor

Leandro Ezequiel Tognola – Agosto 2026
