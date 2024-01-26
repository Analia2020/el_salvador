# Analisis de Sentimiento en Noticias

Este proyecto es la continuación de “Recopilación contenido mediático en el contexto salvadoreño”, en el cual se diseñaron varias herramientas de Web Scraping para recolectar datos de artículos de diarios locales de El Salvador, esta información fue almacenada en una base de datos para ser utilizada en este proyecto.  

Se puede acceder a la app en: https://sentimiento-noticias.streamlit.app/


## Descripcion del proyecto

El objetivo de este proyecto fue construir una herramienta de analisis de sentimiento de noticias en español. 

Para el desarrollo de este proyecto fueron ncesarios los siguientes pasos:

1. *Data Collection*: La recolección de los artículos periodísticos se realizó mediante *web scraping*. Las herramientas fueron diseñadas en un proyecto previo. 

2. *Data preprocessing*: Los artículos seleccionados fueron tratados con técnicas de  Procesamiento de Lenguaje Natural para su posterior análisis

3. *Model development & Evaluation*: Para el análisis de sentimiento se probaron diferentes modelos para analisis de sentimientos en español: Pysentimiento, BERT, Sentiment_analysis_spanish. Luego del analisis inicial se seleccionó el modelo pre-entreado BERT en español.

4. *Streamlit Integration*: 



