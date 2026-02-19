# TelecomX – Predicción de Cancelación de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Estado](https://img.shields.io/badge/Proyecto-Finalizado-brightgreen)
![Tipo](https://img.shields.io/badge/Tipo-Data%20Science-lightgrey)

---

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos predictivos capaces de identificar qué clientes tienen mayor probabilidad de cancelar sus servicios.

Se construyó un pipeline completo que abarca:

- Preprocesamiento de datos  
- Análisis exploratorio  
- Selección de variables  
- Entrenamiento de modelos  
- Evaluación de desempeño  
- Interpretación estratégica  

---


## Objetivos del Proyecto

- Preparar los datos para el modelado (limpieza, codificación y normalización).
- Realizar análisis de correlación y selección de variables.
- Entrenar al menos dos modelos de clasificación.
- Evaluar el rendimiento con métricas adecuadas.
- Interpretar la importancia de las variables.
- Generar conclusiones estratégicas para la empresa.

---

## Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colaboratory  

---

# Cómo Ejecutar el Proyecto

Este proyecto fue desarrollado en **Google Colaboratory**.

## 🛠️ Pasos para ejecutarlo

Para replicar este análisis en la nube, sigue estas instrucciones:

1. **Descargar el archivo:** Baja el archivo `.ipynb` desde este repositorio.
2. **Ingresar a Google Colab:** Accede a [colab.research.google.com](https://colab.research.google.com).
3. **Subir el notebook:** Carga el archivo descargado en la plataforma.
4. **Cargar los datos:** Sube manualmente el archivo CSV cuando el notebook lo solicite utilizando el siguiente bloque de código:

### Código de Carga (Python)

```python
from google.colab import files
uploaded = files.upload() 

# Una vez subido, leer el archivo con pandas
import pandas as pd
df = pd.read_csv("/content/datos_desafio_uno.csv")

