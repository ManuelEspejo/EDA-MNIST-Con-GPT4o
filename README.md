# Análisis de Datos del Conjunto MNIST con GPT4o y otras Exploraciones

En este proyecto, exploramos el conjunto de datos MNIST utilizando técnicas de análisis de datos y la asistencia del modelo GPT4o. Además, entrenamos un modelo simple con Pytorch y evaluamos su rendimiento, investigando posibles causas de discrepancias en su desempeño.

## Índice

- [Análisis de Datos del Conjunto MNIST con GPT4o y otras Exploraciones](#análisis-de-datos-del-conjunto-mnist-con-gpt4o-y-otras-exploraciones)
  - [Índice](#índice)
  - [Objetivos](#objetivos)
  - [Requisitos](#requisitos)
  - [Instrucciones de Ejecución](#instrucciones-de-ejecución)
  - [Descripción Secciones del Notebook](#descripción-secciones-del-notebook)
    - [Carga de Datos y Exploración Inicial](#carga-de-datos-y-exploración-inicial)
    - [Análisis Exploratorio de Datos (EDA) con GPT4o](#análisis-exploratorio-de-datos-eda-con-gpt4o)
    - [Entrenamiento del Modelo](#entrenamiento-del-modelo)
    - [Evaluación del Modelo](#evaluación-del-modelo)
  - [Resultados y Conclusiones](#resultados-y-conclusiones)

## Objetivos

El objetivo es explorar distintas técnicas de análisis de datos, probando la asistencia del modelo GPT4o para disctutir posibles pasos a seguir, y analizar patrones o descubrimientos encontrados en estos datos para extrapolar su uso a conjuntos de datos más complejos en futuros análisis.

## Requisitos

- Python 3.x
- Jupyter Notebook
- Bibliotecas: numpy, pandas, matplotlib, seaborn, torch, torchvision

## Instrucciones de Ejecución

1. Clonar el repositorio

```bash
git@github.com:ManuelEspejo/EDA-MNIST-con-GPT4o.git
```

2. Abrir y ejecutar el notebook `EDA-MNIST-Whith-GPT4o.ipynb` con Jupyter.

## Descripción Secciones del Notebook

### Carga de Datos y Exploración Inicial

En esta sección, cargamos los datos y realizamos una exploración inicial para comprender su estructura y contenido.

### Análisis Exploratorio de Datos (EDA) con GPT4o

Utilizamos técnicas de EDA asistidas por GPT4o para analizar la distribución de clases, valores de píxeles, estadísticas descriptivas, entre otras cosas.

### Entrenamiento del Modelo

Entrenamos un modelo simple utilizando Pytorch para clasificar los dígitos.

### Evaluación del Modelo

Evaluamos el rendimiento del modelo en datos de prueba, identificando posibles problemas y discrepancias en su desempeño durante la inferencia.

## Resultados y Conclusiones

En esta sección, discutimos los resultados obtenidos y se ofrecen conclusiones sobre el desempeño del modelo y posibles soluciones a los problemas encontrados.
