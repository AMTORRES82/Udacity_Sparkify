# Udacity_Sparkify

## Index

1. Libraries.
2. Project Description.
3. File Description.
4. Analysis.
5. Results.
6. Licensing, Authors, and Acknowledgements

## Libraries
You will need the standard data science libraries found in the Anaconda distribution of Python. Especially, the following packages are required:

NumPy
Pandas
Matplotlib
Additionally, PySpark needs to be installed what can be done with pip install pyspark.

## Project Description

Predicting churn is a very common, important and challenging task for companies which business model relies on products with a subscription model. It minimizes customer defection by predicting which customers are likely to cancel a subscription to a service and take actions in order to prevent it.
In this capstone project, Udacity provided a 12 GB dataset of fictitious user interactions with a music streaming company called Sparkify. Whether the user listens to a song, adds it to a playlist or pushes the thumbs up button, all the user activities are logged and can be used for churn prediction. 

The development process for Sparkify churn prediction is divided into three steps:

  1. Exploratory data analysis.
     Load, exploratory analysis, understanding data...
     
  2. Feature engineering.
     Create and transform features.
     New features: Thumbs up/down, songs count, length...
  
  3. Modelling and evaluation.
     3 models tested through a pipeline and hipertuning grid parameters:
     
     3.1 Random Forest Classifier.
     
     3.2 Logistic Regression.
       
     3.3 Gradient-boosted Tree Classifier.
     
     Using the f1 metric the Random Forest is the best model for predicting Churn.
## Files:
   Sparkify(1).ipynb: Notebook where the code is.
   "mini_sparkify_event_data.json": The small data subset we used in this case. Too big for github.
   
   Medium blog
   https://medium.com/@newcastilian/churn-prediction-with-pyspark-6085efce6f7d
## Licensing, Authors, and Acknowledgements
   Thanks to Udacity.
