**INTRODUCTION**

This repository contains the code and models for a sentiment analysis project focused on Turkish movie reviews. 
The project evaluates several machine learning models to determine their efficacy in classifying sentiments expressed in Turkish text. 
The models tested include Logistic Regression, Logistic Regression with N-grams, Support Vector Machines (SVM), SVM with Grid Search, Multi-Layer Perceptrons (MLP), and BERT-Base-Turkish-Cased.

/data/: Contains the training and testing datasets.

/notebooks/: Jupyter notebooks for each model.

/models/: Saved models, including the trained BERT model and its configuration files. (However, pytorch_model.bin file could not be uploaded to Github, so I had to uplaod it to the drive, which you can access through this link: https://drive.google.com/file/d/1ayBccwx60aQZ8ceDbeaBb0tDFb2sZFWj/view?usp=share_link)

environment.yml: Conda environment file for setting up the virtual environment for BERT-Base-Turkish-Cased.

**MODELS**

Logistic Regression (LR): sentiment_LR.ipynb

Logistic Regression with N-grams (LR-N): sentiment_LR_ngrams.ipynb

Support Vector Machine (SVM): sentiment_SVM.ipynb

SVM with Grid Search (SVM-GS): sentiment_SVM_grid_search.ipynb

Multi-Layer Perceptrons (MLP): sentiment_NN_cleaned.ipynb

BERT-Base-Turkish-Cased: sentiment_BERT.ipynb

Each model is detailed within its respective notebook, including its setup, execution, and evaluation.
