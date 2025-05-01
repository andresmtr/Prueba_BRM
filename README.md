# Prueba Data Science

Este repositorio contiene tres notebooks sobre procesamiento de lenguaje natural, predicción de series temporales y transcripción de audio a texto. También contiene un análisis de datos con Power BI de laa base de datos sobre ventas. A continuación se describen brevemente.

## 1. Análisis de Sentimientos en Textos Turísticos (NLP)

* Se entrena un modelo de clasificación de sentimientos en español usando el dataset `alexcom/analisis-sentimientos-textos-turisitcos-mx-polaridad`.  
* Se aplican técnicas como oversampling para balancear las clases y se entrena una red basada en `PlanTL-GOB-ES/roberta-base-bne`.  
* El modelo identifica sentimientos con buen desempeño general, especialmente en clases con mayor representación.

## 2. Predicción de Series Temporales de Demanda

* Se trabaja con datos de demanda por hora y se utiliza un 80% de los datos totales para entrenamiento y prueba, no el 20% como indica la prueba, ya que no es relevante tan pocos datos para el preosesamiento
* Se aplican modelos como `RandomForestRegressor` y `XGBRegressor` para predecir la demanda, y se evalúan los resultados con métricas como RMSE y MAE.  
* El enfoque permite una estimación robusta con pocos datos.

## 3. Transcripción de Audio a Texto (Speech to Text)

* Se utiliza el modelo `Whisper` de OpenAI para convertir archivos de audio a texto.  
* El notebook incluye procesamiento de audios, carga de datos y uso de `datasets` de Hugging Face.  
* Ideal para tareas de reconocimiento de voz o creación automática de subtítulos.

## 4.  de datos con Power Bi - ventas

* Se hacen las conexiones indicadas entre las tablas y se genera una visualizacion por cada item. 
* Se incluye word con análisis de comportamiento



