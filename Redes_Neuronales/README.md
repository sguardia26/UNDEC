# Trabajo Práctico Integrador — Redes Neuronales (UNdeC)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sguardia26/UNDEC/blob/main/Redes_Neuronales/TP_Integrador_Red_Neuronal.ipynb)

Desarrollo y evaluación de una red neuronal (**Perceptrón Multicapa — `MLPClassifier`**) en Python con `scikit-learn` para la clasificación binaria de billetes auténticos vs. falsificados (*Banknote Authentication*).

## Contenido de la carpeta
* [`TP_Integrador_Red_Neuronal.ipynb`](./TP_Integrador_Red_Neuronal.ipynb): Notebook completo con análisis exploratorio (EDA), preprocesamiento sin *data leakage*, entrenamiento de la red neuronal y evaluación de métricas.
* [`dataset_billetes.csv`](./dataset_billetes.csv): Copia limpia del dataset (*1.372 muestras, 4 variables Wavelet + etiqueta binaria `class`*).
* [`requirements.txt`](./requirements.txt): Dependencias de Python necesarias para ejecutar el proyecto.

## Cómo ejecutarlo desde GitHub

### Opción 1: Google Colab (1 clic, sin instalar nada)
Hacé clic en el botón **Open In Colab** de arriba y ejecutá todas las celdas (`Entorno de ejecución → Ejecutar todas`).

### Opción 2: GitHub Codespaces (VS Code en la nube)
1. En el repositorio principal (`sguardia26/UNDEC`), hacé clic en **Code → Codespaces → Create codespace on main**.
2. El entorno se configurará automáticamente mediante `.devcontainer/devcontainer.json` instalando `requirements.txt` y las extensiones de Python y Jupyter.
3. Abrí `Redes_Neuronales/TP_Integrador_Red_Neuronal.ipynb` y ejecutá **Run All**.

### Opción 3: Ejecución local
```bash
git clone https://github.com/sguardia26/UNDEC.git
cd UNDEC/Redes_Neuronales
python -m venv .venv
# En Windows PowerShell:
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```
Luego abrí `TP_Integrador_Red_Neuronal.ipynb` en Visual Studio Code o JupyterLab y seleccioná el intérprete `.venv`.
