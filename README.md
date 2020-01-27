# Predicting bike share availability with H2O and Spark on AWS EMR

Tools Used:
- Spark SQL
- Spark Machine Learning
- H2O ML, Deep Learning and AutoML
- AWS EMR Clusters
- Plotly

Data Source: https://www.kaggle.com/benhamner/sf-bay-area-bike-share

Predict number of bikes available at a given station with:
- station information
- weather condition
- type of day (weekday/weekend)
- hour of the day
- population of the neighborhood

Data Pipeline:
- [Exploratory Data Analysis](EDA_preprocessing.ipynb)
- [Data Visulization with Plotly](EDA_visulization.ipynb)
- [Data Preprocessing and Spark Machine Learning Models on AWS EMR Clusters](EMR_SparkML_modelling.ipynb)
- [H2O ML, Deep Learning, and Auto ML](H2O_modelling.ipynb)

For Spark ML Models, our best model is Random Forest, with an rmse of 2.7  

Group member: Esther Liu, Marine Lin, Akankasha, Lexie
