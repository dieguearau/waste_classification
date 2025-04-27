
## 🧠 Clasificación de Imágenes con CNN y Transfer Learning

Este repositorio contiene el desarrollo del trabajo práctico final de la materia **Visión por Computadora II**. El objetivo es resolver un problema de **clasificación de residuos** mediante imágenes del dataset [TrashNet](https://www.kaggle.com/datasets/feyzazkefe/trashnet/data),utilizando distintos enfoques basados en redes neuronales convolucionales (CNN), incluyendo modelos personalizados y técnicas de **Transfer Learning** con ResNet50.

### 📁 Estructura del Proyecto

- `TP_Final_CVII_Final.ipynb`: Notebook principal con el desarrollo completo del trabajo, que incluye:
  - Carga y preprocesamiento del dataset.
  - Entrenamiento de una CNN desde cero.
  - Aplicación de técnicas de Data Augmentation.
  - Fine-tuning parcial y completo de una **ResNet50** preentrenada.
  - Evaluación de métricas y visualización de resultados.
  - Ajuste de hiperparámetros mediante Optuna.

### 🛠️ Tecnologías y Librerías

- Python 3
- Pytorch
- NumPy, Matplotlib, scikit-learn
- Optuna

### 📊 Resultados

Se comparan distintos enfoques de entrenamiento y ajuste fino. Se analizan los resultados en términos de **precisión**, **matriz de confusión** y curvas de **loss/accuracy**.

### 🚀 Cómo Ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/AzulVillanueva/CEIA-VPC2.git
   ```
2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecutar el notebook en Jupyter o Google Colab.

### 📌 Notas

- El dataset se carga directamente desde kaggle.
- El código está modularizado para facilitar nuevas pruebas y ajustes.
