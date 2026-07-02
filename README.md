
# 📊 EverPeak Retail Analysis | Data Cleaning & EDA Pipeline

¡Bienvenido/a a este repositorio! Este proyecto forma parte del análisis estratégico para el caso **EverPeak–SilverBasket**. 

Trabajé con el dataset `everpeak_retail` (un conjunto de 2,000 órdenes de compra), el cual presentaba desafíos reales de la industria: valores faltantes, registros corruptos (*sentinels*) y anomalías estadísticas (*outliers*). El objetivo principal fue transformar este flujo de datos crudos en un activo limpio y confiable para la toma de decisiones.

---

## 🧠 Objetivos del Análisis

* **Data Quality Assurance:** Identificar fallas de consistencia y anomalías en el set de datos.
* **Pipeline de Limpieza Reproducible:** Construir funciones modulares y escalables en Python para automatizar el tratamiento de datos faltantes y centinelas.
* **EDA Avanzado:** Explorar comportamientos comerciales mediante análisis de distribución y detección de *outliers* (vía IQR y Z-Score).
* **Insights Estratégicos:** Traducir métricas técnicas en recomendaciones de valor para el equipo de Inteligencia Comercial y Operaciones.

---

## 📂 Estructura del Repositorio

* 📁 `notebooks/`
    * └── 📄 `everpeak_analysis.ipynb`: Notebook principal que contiene todo el desarrollo técnico, desde la ingesta y curación de datos hasta la visualización gráfica y conclusiones.

---

## ▶️ Ejecución del Proyecto

### Opción 1: Acceso Directo (Google Colab)
Para explorar el análisis de forma interactiva y sin configuraciones locales, puedes abrir el entorno en la nube con un solo clic:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](TU_URL_DE_GITHUB_AQUÍ)

### Opción 2: Reproducción Local o Paso a Paso
1. Navega hasta la carpeta `notebooks/` y abre el archivo `everpeak_analysis.ipynb`.
2. Ejecuta las celdas de forma secuencial (`Shift + Enter`).
3. El script cuenta con automatización para la carga del dataset directamente desde la ruta de datos especificada, garantizando un entorno *ready-to-run*.

---
_Proyecto desarrollado como parte del programa de especialización en Data Analytics._
