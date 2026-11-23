# 🌾 Segmentación de Unidades Productivas Agrícolas en Colombia

Caso de estudio de **Machine Learning no supervisado** que compara **K-Means** y **DBSCAN** para descubrir perfiles productivos agrícolas a partir de las Evaluaciones Agropecuarias Municipales (EVA) 2019–2025.

## 📌 Problema

En Colombia no existe una clasificación objetiva que distinga entre agricultura de subsistencia, pequeña, mediana y gran escala. Sin esta diferenciación, los subsidios y créditos agrícolas se distribuyen de forma inequitativa.

## 🎯 Solución

Se aplican dos algoritmos de clustering sobre 5.000 registros y 4 variables (área sembrada, área cosechada, producción y rendimiento) para descubrir automáticamente los perfiles productivos, sin usar etiquetas.

## 🏆 Resultado

**DBSCAN** fue seleccionado como algoritmo ganador por su mejor desempeño:

| Métrica | K-Means | DBSCAN |
|---|---|---|
| Silhouette (↑) | 0.619 | **0.735** |
| Davies-Bouldin (↓) | 0.919 | **0.240** |
| Ruido detectado | 0 % | **3.46 %** |

## 📂 Contenido

- `R2-A1-S16 INFORME DE TRABAJO – DISEÑO DE PROYECTO FINAL.ipynb` — Notebook
- `Evaluaciones_Agropecuarias_Municipales_–_EVA._2019_-_2025._Base_Agrícola_20261122.rar` — Dataset
- `R2-A1-S16 INFORME DE TRABAJO – DISEÑO DE PROYECTO FINAL.pdf` — Informe final

## ⚙️ Tecnologías

Python · pandas · NumPy · scikit-learn · matplotlib · seaborn · Google Colab

## 👥 Autores

Carlos Eduardo Riaño Rodríguez · Bryan Felipe Roa Alvarado  
Universidad de Cundinamarca — Introducción a Machine Learning — 2026
