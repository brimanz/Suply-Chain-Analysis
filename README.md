# 🚚 Supply Chain Performance & Optimization Analysis

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-Supply_Chain-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Executive Summary
Este proyecto realiza un análisis integral de la **cadena de suministro y logística** con el objetivo de identificar cuellos de botella operativos, optimizar costos de envío y almacenamiento, y mejorar los tiempos de entrega. A través de técnicas avanzadas de procesamiento de datos y análisis exploratorio (EDA), se transforman datos no estructurados en decisiones estratégicas de negocio.

---

## 🎯 Business Objectives & Key Metrics (KPIs)
El análisis se enfocó en responder preguntas clave del negocio a través de métricas estratégicas:
* **EFICIENCIA LOGÍSTICA:** Evaluación del *On-Time Delivery (OTD)* y detección de demoras en rutas críticas.
* **OPTIMIZACIÓN DE COSTOS:** Análisis del costo total de transporte por unidad, proveedor y modo de envío.
* **GESTIÓN DE INVENTARIOS:** Ratio de rotación de inventarios y análisis de niveles de stock de seguridad.
* **RENDIMIENTO DE PROVEEDORES:** Evaluación del *Lead Time* promedio y cumplimiento de entregas por proveedor.

---

## 📊 Key Insights & Business Impact
1. **Reducción de Costos Logísticos:** Se identificaron inconsistencias en las tarifas de envío por modo de transporte, permitiendo proponer una optimización con potencial de reducción del **12-15% en costos operativos**.
2. **Identificación de Cuellos de Botella:** Determinadas rutas y transportistas mostraron un tiempo de tránsito hasta 25% superior a la media esperada.
3. **Análisis de Proveedores:** Un análisis cruzado (*Lead Time vs. Defect Rate*) permitió segmentar los proveedores según su nivel de riesgo e impacto operativo.

---

## 🛠️ Tech Stack & Tools
* **Lenguaje:** Python 3.x
* **Manipulación & Análisis de Datos:** Pandas, NumPy
* **Visualización de Datos:** Matplotlib, Seaborn / Plotly
* **Entorno de Desarrollo:** Jupyter Notebook / VS Code
* **Control de Versiones:** Git & GitHub

---

## 📁 Repository Structure
```text
├── data/                  # Datasets estructurados (Raw y Processed)
├── notebooks/             # Jupyter Notebooks organizados cronológicamente
│   ├── 01_data_cleaning.ipynb
│   └── 02_exploratory_analysis.ipynb
├── src/                   # Scripts reutilizables y funciones auxiliares
├── visualizations/        # Gráficos y dashboards generados
├── README.md              # Documentación principal del proyecto
└── requirements.txt       # Dependencias necesarias para ejecutar el proyecto
