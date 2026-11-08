# 🛰️ PastizalAI: La brújula inteligente para revivir Picotani 🧭

## 🎬 Demo y presentación

👉 **[Ver la presentación y el video del prototipo (Canva)](https://canva.link/lwzkod9tlhu7h1z)**

Prueba de valor desarrollada en la Datathon CIP 2025 con datos limitados: mapas de carbono y de peso seco (dry weight) estimados con ML, y un dashboard interactivo en Shiny para visualizar mapas y tendencias.

---

## Descripción 🎯

Proyecto para el **análisis, diagnóstico y predicción** sobre pastizales altoandinos (p. ej., carbono, biomasa y cobertura vegetal).

Este repositorio centraliza el desarrollo de modelos de machine learning y la optimización de *pipelines* robustos, sentando las bases para un potencial **Sistema de Alerta Temprana (SAT)** de degradación de suelos en la zona de Picotani.

---

## Estructura del Repositorio 📂

El proyecto se organiza en los siguientes módulos principales:

* **`/Cod_Diagnostico/`** 🔬
    * Notebooks para la limpieza de datos, análisis exploratorio (EDA) y desarrollo de los modelos base de predicción (Ej.: `Prediccion_carbono.ipynb`, `Prediccion_cobertura.ipynb`).

* **`/codigo_optimizacion/`** 📈
    * Scripts y notebooks dedicados a la búsqueda y ajuste fino de hiperparámetros, experimentación y *tracking* de modelos (MLflow, etc.).

* **`/Cod_Sistema_Alerta_Temprana/`** ⚠️
    * Pipelines y notebooks orientados a la detección temprana de anomalías o cambios significativos en series temporales y observaciones espaciales.

* **`/Cod_Shiny/`** 🖥️
    * Código fuente del **Dashboard Interactivo** (desarrollado en Shiny) para la visualización de mapas, tendencias y resultados del análisis.
    
---

*Nota: Cada uno de los directorios contiene su propio `README.md` secundario, explicando en detalle la inicialización, requerimientos y los pasos para la reproducibilidad de esa sección.*

---

## 👥 Equipo (Autores)
Este proyecto fue desarrollado y obtuvo el **2do Puesto en la Datathon CIP 2025** gracias al trabajo colaborativo de:

* **Oscar Cutipa Luque** - [GitHub](https://github.com/OscarCutipaLuque) | [LinkedIn](https://www.linkedin.com/in/oscar-diego-fernando-cutipa-luque/)

* **Cielo Lozada Perez** - [LinkedIn](https://www.linkedin.com/in/cielo-lozada/)

* **Kevin Fernandez** - [LinkedIn](https://www.linkedin.com/in/kevin-fernandez-5a615911a/)

* **Andre Juarez Castro** - [LinkedIn](https://www.linkedin.com/in/andre-juarez-castro/)
