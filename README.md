# TelecomX2025
# 📊 Telecom X - Análisis de Evasión de Clientes

Este proyecto analiza datos históricos de clientes de **Telecom X**, una empresa ficticia de telecomunicaciones, con el objetivo de comprender los factores que influyen en la evasión (churn) de clientes. A través de técnicas de análisis exploratorio y limpieza de datos, se extraen insights clave para proponer estrategias de retención y alimentar futuros modelos predictivos.


## 🎯 Objetivo

- Entender las variables que afectan la evasión de clientes.
- Transformar y preparar los datos para análisis o modelos de machine learning.
- Presentar conclusiones accionables basadas en datos reales.


## 🧠 Lo que se practicó

- Proceso ETL completo (Extracción, Transformación y Carga).
- Manipulación de datos JSON con `pandas`.
- Limpieza y normalización de datos.
- Visualización de datos con `matplotlib` y `seaborn`.
- Análisis de correlación y exploración multivariable.
- Redacción de informes analíticos en entorno colaborativo.

## 📂 Estructura del análisis

### 🔹 Extracción

- Carga de datos desde archivos `.json` estructurados por cliente, servicio y facturación.

### 🔹 Transformación

- Renombrado y estandarización de columnas (`snake_case` y traducción al español).
- Conversión de variables categóricas a numéricas.
- Creación de nuevas variables (`cargo_diario`, `cantidad_servicios`).
- Tratamiento de datos faltantes.

### 🔹 Análisis

- Distribución general del churn.
- Comparación entre variables categóricas y numéricas.
- Visualización de correlaciones relevantes.
- Generación de visualizaciones descriptivas y analíticas.

## 📊 Visualizaciones

Incluye:

- Gráficos de barras y boxplots para análisis comparativo.
- Diagramas de distribución y proporción.
- Heatmap de correlaciones.

## ✅ Recomendaciones finales

- Incentivar contratos más largos.
- Promover servicios empaquetados para reducir el churn.
- Ajustar cargos mensuales altos que puedan contribuir a la evasión.
- Implementar acciones específicas en segmentos vulnerables (clientes sin pareja, con dependientes, etc.).

## 🛠️ Herramientas utilizadas

- **Lenguaje:** Python  
- **Entorno:** Google Colab  
- **Librerías:** `pandas`, `numpy`, `matplotlib`, `seaborn`  
- **Formato de datos:** `.json`
## 📎 Acceso al Notebook

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CGYsWwtHsaz_kEwqvPs9lraU8_NxxJ40)

## 👨‍💻 Autor

**Richard Martínez**  
Ingeniero en Software | Ciencia de Datos  
🔗 [LinkedIn](https://linkedin.com/in/ing-martinez-057b6b18)  
💻 [GitHub](https://github.com/Ingmartinez031)
