# Uso de Redes Neuronales Convolucionales para diagnósticos basados en imágenes médicas
Repositorio que contiene todos los archivos empleados durante la elaboración de la tesis: "Uso de Redes Neuronales Convolucionales para diagnósticos basados en imágenes médicas"

Durante esta tesis se desarrolla una herramienta software capaz de clasificar imágenes de resonancia magnéticas (RMI) de pacientes con esclerosis múltiple (EM) o pacientes de control. Se implementa con el objetivo de ser una herramienta de ayuda al diagnóstico para expertos médicos.

El desarrollo de esta tesis se ha realizado completamente empleando la versión gratuita de _Google Colab_.

## Versiones utilizadas durante el desarrollo de esta tesis 🛠  
Versión de Python:
```
Python 3.7.13
```
Versión de PyTorch:
```
1.12.1+cu113
```

## Datasets 🗒
Los datasets empleados se dividen en función del tipo de imagen RMI empleado:
* Imágenes de vista axial
* Imágenes de vista sagital
* Todas las imágenes

## Directorio de archivos: 🗂
Para cada tipo de dataset se realiza el entrenamiento y evaluación del modelo implementado 5 veces. Esto es debido a las limitaciones de memoria y capacidad de computación disponibles, tanto en el ordenador personal como en la versión gratuita de Google Colab.
* Todas las imágenes:
  - _model_all_01_
  - _model_all_02_
  - _model_all_03_
  - _model_all_04_
  - _model_all_05_
* Imágenes de vista axial
  - _model_axial_01_
  - _model_axial_02_
  - _model_axial_03_
  - _model_axial_04_
  - _model_axial_05_
* Imágenes de vista sagital
  - _model_sagital_01_
  - _model_sagital_02_
  - _model_sagital_03_
  - _model_sagital_04_
  - _model_sagital_05_
  
