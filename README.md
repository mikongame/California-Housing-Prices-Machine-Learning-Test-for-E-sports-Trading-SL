
#  California Housing Prices: Machine Learning Test for-E-sports Trading SL
**Miguel García Melgar**

Este README está por realizar.

* Hay dos documentos "test_ml" y "test_ml-pipe-based".
Las tareas obligatorias de la prueba y algunas opcionales las venía haciendo en el primero, pero como quería ser exhaustivo usando tanto RandomSearchCV como GridSearchCV de forma consecutiva y no tenía claro como hacerlo en un mismo pipeline he optado por hacer un segundo documento en el que hago uso GridSearch dentro de un data pipeline con los parametros del primer notebook (sin hacer RandomSearch).

* Otra cosa relevante es que antes de hacer el Custom Transformer dentro del preprocessing pipeline, los resultados de los modelos eran mejores (los puedes ver en los documentos data/output_csv/old_model_ensambled.csv y data/output_csv/old_models_all.csv), y al ser datos distintos he tenido que repetir toda la parte de fine-tuning. Entre esto y varias caídas de kernel de la maquina virtual que me he montado en Google Cloud, aún tengo el ensemble entrenando por lo que los resultados del final del notebook no corresponden al último modelo. Al menos el codigo está terminado en ambos casos.


## Content
- [Project Description](#project-description)
- [Objective](#objective)
- [Dataset](#dataset)
- [Workflow](#workflow)
  * [Exploratory Data Analysis](#exploratory-data-analysis)
  * [Preprocessing](#preprocessing)
  * [Model Training and Evaluation](#model-training-and-evaluation)
  * [Conclusion](#conclusion)
- [Future improvements](#future-improvements)
- [Tools and requirements](#tools-and-requirements)
- [Links](#links)

## Project Description


## Objective


## Dataset

## Workflow
### Exploratory Data Analysis


### Preprocessing


### Model Training and Evaluation
#### Machine Learning Models

#### Deep Learning Models


#### Fine tuning of the best models


### Conclusion



## Future improvements


## Tools and requirements
In order to finish all the workflow within 3 days I worked on Google Cloud Platform running an instance fo a n1-standard-16 Virtual Machine, which included 16 vCPUs a 60 GB vRAM.

I have also used the lastest versions of the following packages and libraries:
* pandas
* numpy
* math
* seaborn
* matplotlib
* yellowbrick
* sklearn 

## Links
[Repository](https://github.com/mikongame/California-Housing-Prices-Machine-Learning-Test-for-E-sports-Trading-SL)  

