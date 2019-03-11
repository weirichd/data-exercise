# Data Science Engineering Exercise

## Dataset

This exercise uses the Heart Disease UCI dataset from Kaggle.
The zipped dataset is included in the repo.

## Description of files

In this repo, you will find the following files:

* `heart-disease-uci.zip` The dataset. Unzip to get the file `heart.csv`.
* `Heart Model.ipynb` IPython notebook which contains the data analysis, model training, and model testing.
* `final_model.pkl` Saved copy of the final model.

## Packages Used

This project has been tested on Python 3.5. It uses the packages:

* `pandas` For data loading
* `sklearn` For model training

## Instructions

The purpose of this exercise is to take an IPython/Jupyter notebook produced during an experiment by a data scientist and transfer it into a production code.
The notebook contains some analysis, logic to train a new model, and finally a test of that model.
Not all of this code needs to go into the solution.

### Requirements

* Create a Flask (or similar) app which productionizes the code from the notebook. The app should have two endpoints:
  * Train a new model with a new dataset.
  * Use a trained model to make predictions.
* Include both unit tests and acceptance tests.

You are not expected to _deploy_ an app for this exercise, only to produce the code for this app.

Your solution will be evaluated by how well the requirements are met, cleanliness of code, and ease of use.