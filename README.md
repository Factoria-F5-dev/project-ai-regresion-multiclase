# 🎯 Proyecto Clasificación Multiclase

![Banner notebooks](https://github.com/user-attachments/assets/1da2b87c-a4aa-497c-b50c-3596cbf2f375)

## 📝 Descripción del Proyecto

Este proyecto tiene como finalidad desarrollar un modelo de machine learning capaz de resolver un problema real utilizando algoritmos de **clasificación multiclase**. A través de este reto, se busca aplicar todo el conocimiento adquirido sobre análisis de datos, visualización, preprocesamiento, construcción de modelos supervisados y evaluación de resultados.

La **clasificación multiclase** es una tarea de aprendizaje supervisado en la que cada instancia de entrada se asigna a una única clase entre tres o más posibles. A diferencia de la clasificación binaria, donde solo hay dos clases, en la clasificación multiclase el modelo debe aprender a distinguir entre múltiples categorías mutuamente excluyentes.

Como recurso opcional sugerimos este dataset: [**Forest Cover Type Dataset**](https://archive.ics.uci.edu/dataset/31/covertype), solo como sugerencia en caso de no encontrar un dataset adecuado. ¡Más instamos a la autenticidad de vosotrxs!

---

## 📦 Condiciones de Entrega

- El proyecto es **Grupal**.
- Será necesario entregar:
  - Una **aplicación** que reciba datos como entrada y devuelva una predicción multiclase.
  - El **repositorio en GitHub**, con ramas bien gestionadas y commits limpios.
  - Un **informe técnico** con las métricas y análisis del modelo.
  - Una **presentación para negocio** (PowerPoint, Canva, etc.) y una presentación técnica del código.
  - Un **enlace a Trello** u otra herramienta de organización del proyecto.
- El **overfitting** debe ser inferior al **5%**.

---

## 🛠️ Tecnologías a Usar

- Scikit-learn
- Pandas / NumPy
- Streamlit / Dash / Gradio
- Git y GitHub
- Docker

---

## 🏆 Niveles de Entrega

### 🟢 **Nivel Esencial:**  
✅ Un modelo de clasificación multiclase funcional (mínimo 3 clases).

✅ Análisis exploratorio del dataset (**EDA**) con visualizaciones específicas para clasificación (**histogramas por clase, matriz de correlación, etc.**).

✅ Overfitting controlado (menos del **5%** de diferencia entre training y validation).

✅ Aplicación básica que productivice el modelo (**Streamlit, Gradio, Dash**).

✅ Informe con métricas específicas para clasificación multiclase:
- Accuracy global.
- Precision, Recall y F1 por clase.
- Matriz de confusión.
- Feature importance.
- Análisis de errores.

---

### 🟡 **Nivel Medio:**  
✅ Aplicación de **modelos de ensemble** para multiclase (**Random Forest, XGBoost, LightGBM, etc.**).

✅ Implementación de **validación cruzada** (**StratifiedKFold** preferentemente para mantener proporciones por clase).

✅ Optimización de hiperparámetros con técnicas como **GridSearchCV**, **RandomizedSearch**, u **Optuna**.

✅ Sistema de **feedback de usuario** para evaluar predicciones reales vs. esperadas.

✅ Pipeline de **recolección de datos nuevos** para reentrenamiento futuro.

---

### 🟠 **Nivel Avanzado:**  
✅ Dockerización completa del proyecto.

✅ Integración con **bases de datos** para guardar datos recolectados (MySQL, MongoDB, etc.).

✅ **Despliegue en la nube** (Render, Vercel, AWS, etc.).

✅ Implementación de **tests unitarios** para:
- Validar integridad de los datos.
- Comprobar funcionamiento del modelo.
- Confirmar métricas mínimas deseadas.

---

### 🔴 **Nivel Experto:**  
✅ Entrenamiento de **redes neuronales** con soporte para multiclase (CNN si el dataset es visual).

✅ Aplicación de prácticas **MLOps**:
-  **A/B Testing** para comparar modelos.
-  **Monitoreo de Data Drift** con alertas.
-  **Sustitución automática del modelo** si una nueva versión supera las métricas predefinidas.

---

## 🎯 Evaluación

- **Competencia:** Evaluar conjuntos de datos utilizando herramientas de análisis y visualización de datos.
- **Competencia:** Aplicar algoritmos de aprendizaje automático según el problema, identificando y resolviendo problemas clásicos de inteligencia artificial.
