# Trabajo Práctico Integrador — Desarrollo y Evaluación de una Red Neuronal

---

## 1. Datos del Proyecto y del Estudiante

| Campo | Detalle |
| :--- | :--- |
| **Estudiante** | **Guardia, Sebastián Nicolás** |
| **Carrera** | **Tecnicatura Universitaria en Ciencia de Datos** |
| **Asignatura** | **Redes Neuronales** |
| **Institución** | Universidad Nacional de Chilecito (UNdeC) — Escuela de Ingeniería |
| **Problema Abordado** | Clasificación binaria supervisada (*Autenticación de Billetes: Auténtico vs. Falsificado*) |
| **Dataset** | *Banknote Authentication* (UCI Machine Learning Repository / OpenML v1 — 1.372 muestras, 4 variables Wavelet continuas, 0 valores nulos) |
| **Arquitectura de Red** | Perceptrón Multicapa (`MLPClassifier` de `scikit-learn`): 2 capas ocultas `(16, 8)`, activación `ReLU`, optimizador `Adam`, regularización L2 (`alpha=0.01`), escalado con `StandardScaler` sin *data leakage* |

---

## 2. Contenido de la Carpeta

* 📓 [`TP_Integrador_Red_Neuronal.ipynb`](./TP_Integrador_Red_Neuronal.ipynb): Jupyter Notebook completamente documentado y ejecutado (presentación y EDA, preprocesamiento sin fuga de datos, diseño y entrenamiento del `MLPClassifier`, evaluación con matriz de confusión, reporte de clasificación y curva ROC).
* 📊 [`dataset_billetes.csv`](./dataset_billetes.csv): Conjunto de datos limpio exportado automáticamente (`1.372` filas × `5` columnas: `variance`, `skewness`, `curtosis`, `entropy` y etiqueta binaria `class`).
* 🎬 [`TP_Integrador_Red_Neuronal_Video.mp4`](./TP_Integrador_Red_Neuronal_Video.mp4): Video explicativo en primera persona del Trabajo Práctico Integrador en Full HD (`11:57 min`).
* ⚙️ [`requirements.txt`](./requirements.txt): Listado de librerías y dependencias de Python necesarias para reproducir el entorno.

---

## 3. Ejecutar y Probar el Código en Google Colab

Podés abrir, ejecutar y probar todas las celdas del Jupyter Notebook directamente en la nube desde tu navegador haciendo clic en el siguiente botón:

<p align="center">
  <a href="https://colab.research.google.com/github/sguardia26/UNDEC/blob/main/Redes_Neuronales/TP_Integrador_Red_Neuronal.ipynb" target="_blank">
    <img src="https://img.shields.io/badge/🚀_PROBAR_PROGRAMACIÓN_EN_GOOGLE_COLAB-EJECUTAR_NOTEBOOK_AHORA-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Probar en Google Colab" height="48" />
  </a>
</p>

---

## 4. Video Explicativo (Reproducción Online sin Descargar)

Hacé clic en el botón o directamente sobre la pantalla de vista previa para **reproducir el video explicativo en el navegador** (con tu grabación en primera persona sincronizada paso a paso con los 5 bloques del notebook, sin necesidad de descargar el archivo `.mp4`):

<p align="center">
  <a href="https://htmlpreview.github.io/?https://github.com/sguardia26/UNDEC/blob/main/Redes_Neuronales/player.html" target="_blank">
    <img src="https://img.shields.io/badge/▶️_VER_VIDEO_EXPLICATIVO_ONLINE-REPRODUCIR_SIN_DESCARGAR_(11:57)-2ea44f?style=for-the-badge&logo=youtube&logoColor=white" alt="Ver Video Online" height="44" />
  </a>
</p>

[![Reproducir Video Explicativo Online](./preview_video.jpg)](https://htmlpreview.github.io/?https://github.com/sguardia26/UNDEC/blob/main/Redes_Neuronales/player.html)
