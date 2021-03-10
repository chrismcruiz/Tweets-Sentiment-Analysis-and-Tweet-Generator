# Tweets Sentiment Analysis and Tweet Generator using NLP

![Alt text](./Final_project/banner/banner.jpeg?raw=true "Title")


| Integrantes | Código |
| ------------- | ------------- |
| Fredy Alejandro Mendoze  | 2170116  |
| Christian Ruiz Lagos  | 2152204  |


## Motivación del Proyecto

La implementación de la vacuna del COVID-19 ha sido un tema que ha dado mucho de qué hablar. Diferentes personas alrededor del mundo han dejado claro su posición en cuanto a si quieren o no recibir la vacuna, muchas de estas opiniones se hacen públicas a través de redes sociales. Al ser un gran número de personas en diferentes países, es difícil saber cuál es la opinión dominante a nivel mundial, e incluso, la posición general en un entorno local. Analizar esta posición de los habitantes de un país puede ser útil, ya que a partir de esto se puede determinar un estimado de compra de vacunas y desarrollar un cronograma de vacunación óptimo. El fin del proyecto es tener una aproximación a la posición de los colombianos frente al tema de la vacuna a partir de tweets.
Además, la desinformación generada en cuando a la vacunación, ha generado que un porcentaje de colombianos haya adoptado una posición negativa en cuanto a este tema, por lo tanto, es importante crear un medio que divulgue información real y confiable, con el fin de que los colombianos se sientan seguros.

## Objetivos

* Desarrollar un modelo que permita la clasificación de tweets, con el fin de determinar la posición de Colombia frente a la aplicación de la vacuna.
* Implementar un generador de tweets, con el fin de proveer información que incentive la vacunación.


## Descripción del Dataset

El dataset se obtuvo a partir de Web Scrapping. Para ello, recopilamos tweets relacionados con la vacuna del COVID-19.  Para el clasificador, con el fin de realizar un entrenamiento supervisado, recolectamos tweets a partir de los hashtags #YoMeVacuno y #YoNoMeVacuno. Luego de obtener los tweets, realizamos un análisis y aplicamos medidas para obtener solo la información deseada.

Luego de las medidas tomadas, se obtuvieron 7664 tweets. La representación de las clases son:

* 0: Tweet negativo ante la vacuna.
* 1: Tweet positivo ante la vacuna.

Para el generador de texto, obtuvimos información de tweets a partir de filtros (la determinación de los filtros se hizo en base a un análisis previo). En total, se conisguió un dataset con 17120 tweets.

## Modelos Utilizados

* LSTM
* GRU
* GPT-2-small-spanish


## Enlaces de Interés

* [Documentación GPT-2 Small-Spanish](https://huggingface.co/datificate/gpt2-small-spanish)
* [Video descriptivo del proyecto](https://www.youtube.com/watch?v=L4V6qdpRNL0)
* [Modelos implementados para la clasificación de Tweets](https://drive.google.com/drive/folders/1_l0_9S7XjPg_grPhgn-RlSnjb0oOX-EM?usp=sharing)
* [Modelos implementados para la generación de Tweets](https://drive.google.com/drive/folders/13u3_zZ5UyHeH3AyOv7mJlaxMxotjJhLD?usp=sharing)
