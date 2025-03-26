# 🍷 TFG DB3A: Predicción de la Calidad del Vino "Vinho Verde"

Este proyecto de Trabajo de Fin de Grado tiene como objetivo predecir la calidad del vino "Vinho Verde" mediante técnicas de Machine Learning, utilizando exclusivamente variables fisicoquímicas. 
A través de este enfoque, se busca minimizar la subjetividad inherente a las evaluaciones sensoriales realizadas por catadores expertos.

---

## 📌 Objetivos del proyecto

- Predecir la calidad del vino portugués "Vinho Verde" (blanco y tinto) de forma objetiva.
- Sustituir evaluaciones sensoriales subjetivas por análisis fisicoquímico automatizado.
- Optimizar los procesos de toma de decisiones en bodegas y empresas vinícolas.
- Proveer una herramienta escalable para mejorar la competitividad del sector.

---

## 🧪 Dataset

El conjunto de datos incluye 6497 muestras de vino (4898 blancos y 1599 tintos), con variables relacionadas con pruebas fisicoquímicas y una etiqueta de calidad otorgada por catadores.

### 📊 Variables principales

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (target: 0 a 10)

---

## 🛠️ Tecnologías y herramientas

- **Python**: Lenguaje principal.
- **Librerías**: `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`.
- **Jupyter Notebook**: Análisis y visualización del desarrollo.
- **GitHub**: Control de versiones y trabajo colaborativo.

---

## 🔍 Estructura del proyecto

1. **Carga de datos**: Importación del dataset con separación por punto y coma.
2. **EDA (Análisis Exploratorio)**: Visualización y comprensión de las variables.
3. **Preprocesamiento**: Estandarización, codificación y limpieza de datos.
4. **Feature Selection**: Identificación de las variables más relevantes.
5. **Modelización**: Uso de algoritmos (ej. redes neuronales) para entrenar modelos predictivos.
6. **Evaluación**: Métricas como MAE y R² para medir el rendimiento del modelo.

---

## ⚙️ Ejecución del proyecto

### Requisitos

Instala los paquetes necesarios con:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
