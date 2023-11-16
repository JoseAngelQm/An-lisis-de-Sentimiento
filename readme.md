# Analisis de Sentimiento utilizando redes neuronales LSTM
## Autor : 
           José Angel Quispe Meza

## Introducción
En la era digital, la explosión de datos en plataformas de redes sociales como Twitter ha brindado una ventana única hacia la expresión humana en tiempo real. Este vasto torrente de información se ha convertido en un terreno fértil para el análisis de sentimientos, una disciplina en constante evolución que fusiona la potencia del Procesamiento del Lenguaje Natural (PLN), Machine Learning y las sofisticadas Redes Neuronales Recurrentes, específicamente, las LSTM (Long Short-Term Memory).

En este contexto, nos embarcamos en una travesía para desentrañar las complejidades del lenguaje humano en Twitter, centrándonos en el análisis de sentimientos de un singular post. El procesamiento de lenguaje natural actúa como nuestra brújula, permitiéndonos navegar a través de la vastedad de expresiones lingüísticas. Las redes neuronales LSTM, con su capacidad única de entender contextos y dependencias temporales, se erigen como el bastión de nuestra exploración. Impulsados por técnicas avanzadas de Machine Learning, nuestro objetivo es no solo interpretar las palabras, sino también captar las matices emocionales, revelando así las complejidades detrás de un simple tweet.

# Objetivos

## Objetivo General
Implementar un modelo de redes neuronales con el propósito de clasificar de manera precisa, mediante un enfoque de Análisis de Sentimientos.

## Objetivos Específicos

* Recopilar datos de Twitter utilizando EXPORT COMMENTS.
* Realizar preprocesamiento de datos extraídos para eliminar, corregir o transformar cualquier información irrelevante.
* Etiquetar la polaridad, utilizando el paquete de Python 'sentiment-analysis-spanish', para crear un conjunto de datos de entrenamiento.
* Realizar un EDA de los tweets.
* Entrenar un modelo de red neuronal LSTM Bidireccional para la clasificación.
* Evaluar la red neuronal LSTM Bidireccional.

## Extracción de datos
Para obtener estos comentarios se utilizó la herramienta libre:
https://es.exportcomments.com/
La cual permite extraer 100 comentarios de cualquier publicación de red social en su versión gratuita. 
La página hece uso de la librería de python Beautiful Soup, que le facilita la función de web scraping, para la extracción de datos.

## Conclusiones
*  Se plantea la posibilidad de evaluar el rendimiento del etiquetado del conjunto de entrenamiento mediante la clasificación manual de polaridades o sentimientos, comparándolo con los resultados obtenidos mediante el paquete de etiquetado en español, sentiment-analysis-spanish.
*  Respecto a la eliminación de stopword sería interesante explorar en trabajos futuros los resultados obtenidos cuando estas palabras no son eliminadas. Este análisis podría proporcionar más contexto al dato textual.
*  Este análisis reveló que una gran parte de las opiniones publicadas por los usuarios hispanohablantes pertenecen a las categorías de neutro y negativo
*  El modelo de LSTM creado debe ser ajustado para poder dar mejores resultados si se desea   aplicar en otras publicaciones.
*  El modelo de Random forest muestran un rendimiento perfecto.

## link de diapositiva
https://docs.google.com/presentation/d/1jdSxYTIlbVp_zfBhvVWCB4KQG0EBXEmb/edit?usp=drive_link&ouid=110783436576028575700&rtpof=true&sd=true