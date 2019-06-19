# Disaster Response Pipeline Project

For this project I created NLP (Natural Language Processing) Pipelines in order to process and categorize messages sent during various natural disaster events. It is a project requierd by Udacity in order to get Data Science Nanodegree. This pipelines are part of an web app. The code for the web app was provided by Udacity team. The visualisations are mine. 

## Installation

Following libraries are needed in order for the web app to run:

- numpy
- pandas
- sklearn
- sqlalchemy
- pickle
- sys
- re
- nltk
- json
- plotly
- flask

## Components of the repository

### app

The app contains files necessary to run the webapplication (Flask)

### data

This file contains the ETL pipeline for the data. It is a data extracting, cleaning and processing pipeline. It also contains the data as csv files. Data can be found by Figure Eight: https://www.figure-eight.com/

### models

The file models contains the training file for the machine learning pipeline (ML Pipeline). It loads the data from the SQLite database and trains and tunes the model using GridSeachCV. The pickle file contains the saved model.

### notebooks

Jupyter notebooks contain preparatory work for the app. First noetebook contains data preprocessing (ETL pipeline). Second notebook contains the ML pipeline. The notebooks are not the same as the app. 

## Licensing
Parts of the code for this project were provided by Udacity. The data for this project comes from Figure Eight. Otherwise the project is freely usable. 
