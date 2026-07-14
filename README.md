# Modelo-de-predicción-tiendas-online
Este proyecto busca brindar una herramienta de análisis a las tiendas con e-commerce para predecir que usuarios realizarán una compra efectiva o abandonarán el carrito de compras. La idea es acercarle a la tienda la probabildiad de que se efectivice o no esa compra. Dicho esto, se utilizó un modelo de machine learning ya que al ser un trabajo de predicción era el recurso más conveniente. 

Para ello se trabajó con datos de navegación y comportamiento de usuarios, utilizando variables asociadas a visitas, duración de sesiones, fuente de tráfico, tipo de visitante y conversión. 

El objetivo final es identificar patrones de comportamiento que permitan anticipar si un usuario finalizará una compra o abandonará el proceso.

## Web
Se adjunta el link de la página web, creada con streamlit y en web se puede ver el código de streamlit (app.py) y las librerías necesarias
https://buyerpredict-epmzkf30awa.streamlit.app/ 

## Notebook
En esta sección se presenta el código elaborado a lo largo de todo el proyecto, basado en el modelo de Random Forest que luego se conecta a la web de Streamlit

## Docs
En este apartado se encuentra el informe elaborado durante el desarrollo del proyecto, las complicaciones presentes y recomendaciones en caso de querer realizar este proyecto

## Datos
El dataset utilizado como referencia es `Online Shoppers Purchasing Intention Dataset`.

Fuente:  
https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

Los archivos de datos no se incluyen en este repositorio.

Para reproducir el proyecto, se debe crear una carpeta llamada `data/` y colocar allí los archivos:

```text
data/
├── online_shoppers_intention.csv
└── datos_tiendanube.csv
El primer dataset corresponde al utilizado para el entrenamiento del modelo y el segundo corresponde al dataset que debería publicar la tienda online con sus datos propios para el análisis.





