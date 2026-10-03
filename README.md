# Evaluación Final Unidad I: Minería de Datos (CRISP-DM)

**Autor:** Jose Aravena  
**Repositorio:** `evaluacion-U1_jose-aravena`  
**Asignatura:** Minería de Datos / Data Mining  

---

Descripción del Proyecto

Este proyecto aplica la metodología **CRISP-DM** para abordar la problemática de riesgo y desempeño académico estudiantil. A través de técnicas de analítica exploratoria, **Reglas de Asociación (Algoritmo Apriori/FP-Growth)** y **Modelos de Clasificación (Árboles de Decisión)**, se buscan identificar factores clave de riesgo pedagógico para la toma de decisiones preventivas por parte de Equipos Docentes y Directores de Carrera.

---

Estructura del Repositorio

* `Evaluacion_1_Jose_Aravena.ipynb`: Jupyter Notebook con el desarrollo completo del proyecto paso a paso en Google Colab.
* `README.md`: Documentación e introducción general del repositorio.

---
Fases Metodológicas Desarrolladas (CRISP-DM)

1. **Business Understanding:** Definición del problema académico, alineación con stakeholders y formulación de preguntas de negocio.
2. **Data Understanding:** Análisis del dataset, diccionarios de variables y tipos de datos.
3. **Data Preparation:** Tratamiento de datos faltantes (imputación por mediana y moda), discretización en tramos y prevención de *Data Leakage*.
4. **Modeling:**
   * **Reglas de Asociación:** Filtrado de combinaciones relevantes con $Lift > 1$ orientadas a riesgo bajo (`performance_level_Low`).
   * **Árbol de Decisión:** Entrenamiento de modelo explicativo con `max_depth=3` para extracción de reglas claras.
5. **Evaluation:** Evaluación de desempeño y extracción de insights clave para la gestión educativa.

---

Tecnologías Utilizadas

* **Lenguaje:** Python 3
* **Entorno:** Google Colab / Jupyter Notebooks
* **Librerías Principales:** `pandas`, `numpy`, `matplotlib`
