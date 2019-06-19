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

This file contains the ETL python pipeline for the data. It is a data extracting, cleaning and processing piepline. It also contains the data as csv files. Data can be found by Figure Eight: 


### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/
