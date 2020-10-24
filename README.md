
#  California Housing Prices: ML Test for-E-sports Trading SL
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
That was technical test I had to do during a recruitment process for a Junior Data Scientinst position in a company that made e-sport results prediction for trading. The test used this dataset from Kaggle, [California Housing Prices](https://www.kaggle.com/camnugent/california-housing-prices) ,originally used in the second chapter of Aurélien Géron's recent book 'Hands-On Machine learning with Scikit-Learn and TensorFlow', which holds information from the 1990 California census.

## Objective
You are hired as a Data Scientist at a top real state company in California, and you first job is to develop an ML model to predict house prices. This model will then be used as an investment tool in your company, to buy houses when their price is lower than their real value or negotiating overprices.

## Dataset
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. Be warned the data aren't cleaned so there are some preprocessing steps required! The columns are as follows, their names are pretty self explanitory:

*longitude
*latitude
*housingmedianage
*total_rooms
*total_bedrooms
*population
*households
*median_income
*medianhousevalue
*ocean_proximity

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

