# Predictly – Mini proyecto MLOps

## Descripción
Predictly es un proyecto personal de **MLOps básico** que demuestra el pipeline de un modelo de clasificación desde entrenamiento hasta predicción.  

Objetivo: entrenar un modelo simple con Python y scikit-learn, documentar el flujo y mostrar potencial para despliegue y automatización de pipelines en producción.

---

## Dataset
Se utiliza el **dataset Iris**, que contiene 150 flores de 3 especies distintas (`setosa`, `versicolor`, `virginica`) con 4 características: largo y ancho del pétalo, largo y ancho del sépalo.

---

## Modelo
- Algoritmo: Random Forest Classifier
- Métrica: Accuracy sobre conjunto de prueba
- Guardado con `joblib` para futuras predicciones

---

## Uso
1. Instalar librerías:
```bash
pip install -r requirements.txt

