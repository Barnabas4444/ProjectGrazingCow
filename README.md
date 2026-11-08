# ProjectGrazingCow
Repository for the main Deep learning in Python homework
Team Members:

Faludi Zsófia - B4ZPWB

Danyi Kristóf - GQOKMW

Szemán Barnabás - ZKR2O5

Project Overview: Is there enough grass in the pasture for the herd? Estimating how much forage is available helps farmers decide when to let their animals graze and when to give the pasture time to recover. The CSIRO – Image2Biomass Prediction Kaggle competition challenges participants to estimate pasture biomass from photographs. The dataset contains images of Australian pastures from different regions and seasons, with varying mixes of plant species. The images are accompanied by field measurements of biomass and NDVI values that describe vegetation condition. The task is to predict five biomass values, each measured in grams.


Uploaded files: 


test: Contains the uploaded test image.

test.csv: Lists the test image and the target variables to predict in a CSV format the code can read.

train_small_images: Contains a subset of 30 images from the Kaggle training dataset in PNG format.

train_small.csv: Contains the training records for the 30 images in train_small_images.

data_preparation.ipynb: This notebook loads, analyzes, and visualizes the data.

pasture_biomass_tensorflow.ipynb: In this notebook, we train a TensorFlow model to estimate five biomass values in grams from a pasture photograph. At the end, we use the model to generate predictions for the test images.
