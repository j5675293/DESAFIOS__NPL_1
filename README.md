
[![a](https://www.fi.uba.ar/images/logo-fiuba.png)
# DESAFIOS DE PROCESAMIENTO DE LENGUAJE NATURAL I
### Especialización en Inteligencia Artificial

Los desafios ejecutados correspondientes a Procesamiento de Lenguaje Natural I, de la Especialidad en Inteligencia Artificial
## Desafio I
- Se ejecutó la **vectorización de documentos**. Se tomó 5 documentos al azar y se midió la similaridad coseno con el resto de los documentos.
- Se entrenó modelos de **clasificación Naïve Bayes** para maximizar el desempeño de clasificación (f1-score macro) en el conjunto de datos de test.
- Se ejecutó la **transposición de la matriz documento-término**. De esa manera se obtuvo una matriz término-documento que puede ser interpretada como una colección de vectorización de palabras.-

## Desafio II
- Se utilizó documentos / corpus para crear embeddings de palabras. Se utilizó **canciones de bandas** para generar los embeddings.
- Se ejecutó la eliminación de caracteres especiales y números, tokenización,, eliminación de stopwords en inglés y lematización de palabras.
- Se utiliza Word2Vec de Gensim con arquitectura Skip-gram, vectores de dimensión 100,  y los parámetros optimizados para corpus de canciones.
Tres visualizaciones diferentes con Plotly: Mapa general de los embeddings de las palabras más frecuentes, análisis por categorías semánticas (emociones, tiempo, personas) y conexiones semánticas entre palabras clave.
- Se realizó ánalisis de agrupamiento y conexiones semanticas de palabras. 

## Desafio III
- Para entrenar el modelo de lenguaje se trabajó con dataset de **Corpus TASS-2020** es un conjunto de datos en español diseñado para tareas de análisis de sentimientos y análisis semántico.
- Se realizó pretratamiento de dataset y separación entre datos de entrenamiento y validación. Se realiza la división de muestras en **entrenamiento (train)** y **validación (dev)**.
- Se ejecutó diferentes arquitecturas de redes neuronales basadas en unidades recurrentes.
- Se entreno el modelo con; Multilayer, LSTM y GRU.

## Desafio IV
- Para este desafio se utilizó dataset disponible del challenge **ConvAI2** (Conversational Intelligence Challenge 2) de conversaciones en inglés. 
    
        import kagglehub
		# Download latest version
		path = kagglehub.dataset_download("danielwillgeorge/glove6b100dtxt")
		print("Path to dataset files:", path)
    

- Se construyó  un** BOT** para responder a preguntas del usuario (QA)
- Se ejecutó el preprocesamiento con: *word2idx_inputs, max_input_len word2idx_outputs, max_out_len, num_words_output encoder_input_sequences, decoder_output_sequences, decoder_targets*.
- Para embeddings se utilizó de **Glove** o FastText para transformar los tokens de entrada en vectores.
- El entrenamiento de modelo fue basado en el esquema encoder-decoder.
- Se ejecutó inferencia. 

