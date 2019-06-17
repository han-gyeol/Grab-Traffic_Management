# Grab-Traffic_Management

This repository is for the submission purpose of Grab AI for SEA Traffic Management Challenge.

Libraries required: numpy, pandas, geohash, pickle, sklearn, xgboost, annoy
All libraries can be downloaded by 'pip install [library name]'

1. 'XGboost_train.ipynb' notebook is to train the XGBoost Regressor model from given traffic demand data
2. 'XGboost_test.ipynb' notebook is to test the trained XGBoost Regressor model with test dataset

To run the program, sipmly edit the path to the dataset and run through the notebook.

Apart from given features, there are two additional features preprocessed and used for prediction:
1. Demand values of previous days
2. Demand values of nearest neighbours

Explanations of each feature is written inside the notebook