 Telecom X – Análisis de Evasión de Clientes (Churn)


                                                                           Descripción del Proyecto

La evasión de clientes (churn) es uno de los principales desafíos en la industria de las telecomunicaciones, ya que impacta directamente en los ingresos y la sostenibilidad del negocio.
Este proyecto analiza datos de clientes de Telecom X con el objetivo de identificar los factores más relevantes asociados a la evasión y generar insights accionables que apoyen estrategias de retención y modelos predictivos.

    Objetivos

Comprender la magnitud y el comportamiento del churn

Identificar los principales factores que influyen en la evasión de clientes

Apoyar el desarrollo de futuros modelos predictivos

Proporcionar recomendaciones estratégicas orientadas al negocio

 Dataset

El dataset contiene información a nivel cliente, incluyendo:

Datos demográficos

Información contractual y de facturación

Servicios contratados

Métodos de pago

Indicador de evasión (churn)

Los datos fueron obtenidos desde una API pública en formato JSON y procesados utilizando Python y Pandas.

Limpieza y Preparación de Datos

Las principales tareas realizadas fueron:

Carga de datos directamente desde una API

Normalización de estructuras JSON anidadas

Tratamiento de valores nulos e inconsistencias

Conversión de variables categóricas (Sí/No) a formato binario

Estandarización de nombres de columnas al inglés

Creación de una variable derivada: daily_charges (cargo diario)

Estos pasos garantizaron la calidad y consistencia de los datos para su análisis.

Análisis Exploratorio de Datos (EDA)

El análisis exploratorio se enfocó en comprender el comportamiento del churn mediante:

Distribución general de clientes con y sin churn

Análisis de churn según variables categóricas:

Tipo de contrato

Método de pago

Tipo de servicio de internet

Comparación de churn con variables numéricas:

Antigüedad del cliente (meses)

Cargos mensuales, totales y diarios

Se utilizaron gráficos de barras y boxplots para identificar patrones y diferencias relevantes.

 Principales Hallazgos

Los clientes con contratos mensuales presentan la mayor tasa de evasión

El churn se concentra principalmente en clientes con baja antigüedad

Cargos mensuales y diarios elevados están asociados a mayor probabilidad de churn

El método de pago electronic check muestra mayores tasas de evasión

La ausencia de soporte técnico y servicios de seguridad incrementa el riesgo de cancelación

Recomendaciones de Negocio

Incentivar contratos de mayor duración (anuales y bianuales)

Implementar estrategias de retención temprana para clientes nuevos

Revisar la estructura de precios en segmentos de alto riesgo

Promover métodos de pago automáticos

Incluir servicios de valor agregado como soporte técnico y seguridad

 Herramientas y Tecnologías

Python

Pandas

Matplotlib

Jupyter Notebook

 Próximos Pasos

Ingeniería de características para Machine Learning

Desarrollo y evaluación de modelos predictivos de churn

Segmentación de clientes y estrategias avanzadas de retención
