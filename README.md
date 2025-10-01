# 🎬 *Sentimientos en Pantalla: ¿Aplausos o Abucheos?*
Film Junky Union, una nueva comunidad vanguardista para los aficionados de las películas clásicas, está desarrollando un sistema para filtrar y categorizar reseñas de películas. El objetivo es entrenar un modelo para detectar las críticas negativas de forma automática. Para lograrlo, se utilizó un conjunto de datos de reseñas de películas de IMDB con leyendas de polaridad para construir un modelo para clasificar las reseñas positivas y negativas. 
## Clasificación de reseñas de películas con modelos de Machine Learning
Este proyecto tiene como objetivo construir un modelo capaz de **clasificar reseñas de películas** según su **sentimiento**: positivo o negativo. A partir de un conjunto de datos de IMDb, se desarrollaron y compararon diferentes enfoques utilizando herramientas de procesamiento de lenguaje natural (NLP) como **NLTK**, **spaCy**, **TF-IDF**, y algoritmos como **Regresión Logística** y **LGBMClassifier**.
Además, se comenzó a explorar el uso de **BERT**, un modelo de lenguaje profundo basado en redes neuronales, para generar representaciones vectoriales más sofisticadas de los textos. **Sin embargo, el modelo BERT solo se utilizó con una pequeña muestra de los datos (200, 50)**.
Este proyecto representa un paso importante para entender cómo se pueden aplicar diferentes técnicas de NLP y machine learning para analizar el lenguaje humano y predecir emociones en texto de forma automática.

### Descripción de los datos
Los datos se almacenan en el archivo imdb_reviews.tsv.
Para descargar, visitar el siguiente link: https://practicum-content.s3.us-west-1.amazonaws.com/datasets/imdb_reviews.tsv?etag=bbd4a8dc10e6cf1280c42d7350105c41
Los datos fueron proporcionados por Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, y Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. La Reunión Anual 49 de la Asociación de Lingüística Computacional (ACL 2011).

**Aquí se describen los campos seleccionados:**
- **review:** el texto de la reseña
- **pos:** el objetivo, '0' para negativo y '1' para positivo
- **ds_part:** 'entrenamiento'/'prueba' para la parte de entrenamiento/prueba del conjunto de datos, respectivamente
