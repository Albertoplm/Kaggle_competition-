# Kaggle_competition

## Description

- The aim of this competition is to find the best machine learning model and params for a given dataset. 

## Instructions

Find the Kaggle competition with your cohort name, i.e. **diamonds-datamad0321**, https://www.kaggle.com/c/diamonds-datamad0321

### train.csv
* 1. **Processing/cleaning** the dataset: this should be later modularized in functions.
* 2. **Train** a model (fit & predict) with the data in `train.csv`. This file does contain a **y**.
        - Do *train, test, split* on `train.csv` if necessary.
        - Choose the best model regarding the metrics. In this case, the lowest MSE (error).

        2.1. **Export** the model: we don't want to invest time/RAM resources on training the model again in the future.

### test.csv
* 3. Apply the same **cleaning** to `test.csv`. This files does NOT contain a **y**.
* 4. We'll apply the already **trained model** from step 2 to the `text.csv` file. With this we'lñl generate a new column with the predicted values.  

### my_submission.csv

* 5. Generate a `submission.csv` file with only two columns: the **ID** of the diamond & the predicted **price** (y).


