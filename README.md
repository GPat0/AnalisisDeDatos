📊 Danu Analítica – Dashboard de Analítica Predictiva y Toma de Decisiones
🧠 Descripción del proyecto

Este repositorio contiene el desarrollo de un dashboard interactivo de analítica avanzada, enfocado en el análisis de ingresos, pedidos y desempeño logístico, con integración de modelos de Machine Learning para predicción de ingresos futuros.

El proyecto fue desarrollado como parte de un ejercicio de analítica aplicada, con un enfoque en visualización ejecutiva, análisis de tendencias y apoyo a la toma de decisiones estratégicas.

🖥️ Vista general del dashboard

El dashboard permite visualizar de forma clara e interactiva:

Ingresos totales y su variación interanual

Total de pedidos

Valor promedio por pedido

Costo promedio de flete

Tendencia mensual de ingresos con predicción del siguiente mes

Distribución de ingresos por región

Distribución por categoría de producto

Además, incorpora filtros dinámicos por:

Periodo

Región

Categoría

Y un módulo de recomendaciones estratégicas que simula el impacto de acciones operativas sobre los resultados.

📈 Funcionalidades principales

Dashboard interactivo desarrollado con Streamlit

Visualizaciones dinámicas con Plotly

Comparación entre datos históricos y valores predichos

Gráfica de tendencia mensual con proyección futura

Análisis por región y categoría

Carga dinámica de datasets (CSV, Excel, Parquet)

Indicadores clave (KPIs) orientados a negocio

Alertas y análisis visual para detectar caídas relevantes

🤖 Modelos de Machine Learning

Para la predicción de ingresos se implementaron modelos ensemble:

Random Forest Regressor

XGBoost Regressor

Los modelos consideran variables como:

Estacionalidad

Variables de calendario

Tendencias históricas

Eventos especiales

Factores económicos y operativos

El modelo genera un archivo de salida con la predicción del siguiente mes, que se integra directamente al dashboard para su visualización.

🛠️ Tecnologías utilizadas

Python

Streamlit

Pandas / NumPy

Plotly

Scikit-learn

Random Forest

XGBoost

Archivos CSV y Parquet

🎯 Objetivo del proyecto

El objetivo principal es demostrar cómo la analítica de datos y el Machine Learning pueden utilizarse para:

Anticipar comportamientos futuros

Identificar riesgos y oportunidades

Facilitar la toma de decisiones basada en datos

Traducir datos complejos en visualizaciones claras y accionables

👨‍💻 Rol y aportación personal

Desarrollo completo del dashboard interactivo

Limpieza y preparación de datos

Implementación e integración de modelos predictivos

Diseño de visualizaciones orientadas a negocio

Interpretación de resultados y generación de insights
