# Comparación de modelos de clasificación: Árbol de Decisión vs. SVM

Este repositorio contiene la resolución de una actividad de **Aprendizaje Supervisado**, en la que se comparan dos modelos de clasificación vistos durante el bloque de la materia:

- **Árbol de Decisión**
- **Support Vector Machine (SVM) lineal**

El objetivo del trabajo es aplicar ambos modelos sobre un mismo dataset, evaluar su desempeño y determinar cuál aborda mejor el problema de clasificación planteado.

---

## Dataset utilizado

Se trabajó con el dataset **Banknote Authentication**, disponible en el repositorio público **UCI Machine Learning Repository**.

Este conjunto de datos contiene:

- **1372 registros**
- **4 variables numéricas**
- **1 variable objetivo binaria**

El problema consiste en clasificar registros de billetes a partir de características numéricas extraídas de imágenes.

---

## Desarrollo del código

La notebook incluye las siguientes etapas:

1. Carga del dataset.
2. Exploración inicial de los datos.
3. Revisión de valores faltantes.
4. Análisis de la distribución de clases.
5. División entre conjunto de entrenamiento y prueba.
6. Entrenamiento de un modelo de **Árbol de Decisión**.
7. Entrenamiento de un modelo **SVM lineal**.
8. Evaluación de ambos modelos mediante:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Matriz de confusión
9. Comparación final de resultados.
10. Conclusión sobre el modelo con mejor desempeño.

---

## Resultados obtenidos

Los dos modelos alcanzaron un muy buen rendimiento, aunque el **Árbol de Decisión** obtuvo mejores métricas generales.

| Modelo | Accuracy | Precision | Recall | F1-score |
|---|---:|---:|---:|---:|
| Árbol de Decisión | 0.9927 | 0.9928 | 0.9927 | 0.9927 |
| SVM lineal | 0.9745 | 0.9759 | 0.9745 | 0.9746 |

A partir de estos resultados, se concluye que el **Árbol de Decisión** fue el modelo que mejor resolvió este problema de clasificación para el dataset utilizado.

---

## Presentación en video

Como parte de la entrega, se realizó una presentación grabada en la que se explica:

- El problema de clasificación seleccionado.
- El dataset utilizado.
- El funcionamiento general de cada modelo.
- La evaluación de sus resultados.
- La comparación final y la conclusión.

### Enlace al video

(https://youtu.be/DU648STzifA)

---

## Archivos del repositorio

- `Clase6_GonzaloOrtiz_AprendizajeAutomatico.ipynb`: notebook con el desarrollo completo del trabajo.
- `README.md`: descripción general de la actividad.
