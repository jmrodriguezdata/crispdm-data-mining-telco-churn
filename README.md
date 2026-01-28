# crispdm-data-mining-telco-churn

Autor: Juan Miguel Rodríguez Trujillo


## 📌 Descripción del proyecto
Proyecto **end-to-end de Data Mining aplicado a churn en telecomunicaciones**, que recorre el ciclo completo de la metodología **CRISP-DM**, desde el entendimiento del negocio hasta la evaluación de un modelo de **regresión logística**, documentado en un **reporte HTML orientado a la toma de decisiones**.

Este repositorio prioriza el **proceso analítico completo y bien estructurado** sobre la complejidad algorítmica, con un enfoque práctico, reproducible y comunicable.

---

## 🎯 Objetivo del proyecto

### Objetivo general
Desarrollar un caso aplicado de minería de datos que ilustre de forma clara y completa el uso de la metodología **CRISP-DM** para el análisis y predicción de churn en el sector de telecomunicaciones.

### Objetivos específicos
- Comprender el problema de churn desde una perspectiva de negocio.
- Explorar y entender la estructura del dataset Telco Customer Churn.
- Preparar los datos mediante limpieza, transformación y codificación de variables.
- Implementar un modelo de **regresión logística** como técnica de clasificación interpretable.
- Evaluar el desempeño del modelo mediante métricas estándar.
- Comunicar los resultados a través de un **reporte HTML claro y visualmente amigable**.

---

## 🧠 Metodología: CRISP-DM

El proyecto sigue las seis fases clásicas de CRISP-DM:

1. **Business Understanding**  
   Definición del problema de churn, contexto del negocio y objetivos analíticos.

2. **Data Understanding**  
   Exploración inicial del dataset, análisis descriptivo y detección de inconsistencias.

3. **Data Preparation**  
   Limpieza de datos, tratamiento de valores faltantes, transformación de variables y codificación.

4. **Modeling**  
   Entrenamiento de un modelo de **regresión logística** para la predicción de churn.

5. **Evaluation**  
   Evaluación del modelo mediante métricas como accuracy, precision, recall, F1-score y matriz de confusión, con énfasis en la interpretación de resultados.

6. **Deployment (conceptual)**  
   Discusión de posibles usos del modelo y recomendaciones para su implementación en un contexto real.

---

## 📂 Estructura del repositorio

```text
crispdm-data-mining-telco-churn/
│
├─ Entregable/                      # Reporte HTML final y recursos asociados (imágenes, estilos)
├─ EDA_Telco+CRISP-DM.ipynb # Notebook principal con todo el flujo CRISP-DM
├─ WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset utilizado en el análisis
├─ README.md                        # Descripción del proyecto
├─ requirements                     # Dependencias del proyecto
└─ .gitignore                       # Archivos ignorados por Git

