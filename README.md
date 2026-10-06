# Diagnóstico de Neumonía mediante Análisis de Radiografías

## Descripción
Este proyecto implementa un sistema de diagnóstico asistido por computadora para detectar neumonía a partir de radiografías de tórax. A diferencia de los enfoques simples de clasificación, nuestro sistema primero detecta y localiza regiones opacas en los pulmones antes de realizar el diagnóstico, imitando mejor el proceso de diagnóstico médico real.

## Características
- Detección automática de regiones opacas en radiografías de tórax
- Análisis avanzado de imágenes médicas  
- Diagnóstico basado en la localización de patrones específicos
- Resultados interpretables con visualización de áreas de interés

## Tecnologías
- Procesamiento de imágenes médicas
- Técnicas de visión por computadora
- Modelos de deep learning
- Detección y segmentación de objetos

## Datos
El dataset no se incluye en el repositorio por las condiciones de uso de la competición. Descárgalo de la [RSNA Pneumonia Detection Challenge](https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/data) en Kaggle (hay que aceptar sus reglas) y colócalo así:

```
data/
├── stage_2_train_images/          # DICOM de entrenamiento
├── stage_2_test_images/           # DICOM de test
├── stage_2_train_labels.csv
├── stage_2_detailed_class_info.csv
└── stage_2_sample_submission.csv
```

`data/yolo_data/` (imágenes y etiquetas en formato YOLO) se genera con `notebooks/02_modeling.ipynb`, y los modelos entrenados se guardan en `data/models/`.

## Instalación
Requiere Python 3.12. Ver [env_info.txt](env_info.txt) para más detalles.

```
py -3.12 -m venv pneumonia_env
pneumonia_env\Scripts\activate
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128
pip install -r requirements.txt
```

## Uso
*Instrucciones de uso pendientes*

## Contribución
*Guías de contribución pendientes*

## Licencia
*Información de licencia pendiente*

## Contacto
*Información de contacto pendiente*
