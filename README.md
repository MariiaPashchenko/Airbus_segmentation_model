# Airbus_segmentation_model
This is a solution for Kaggle ship detection competition https://www.kaggle.com/c/airbus-ship-detection

It is based on U-Net convolutional network implemented in Tensorflow.keras.

#### Data
Train dataset consists of 192k images most of that doesn't contain ships at all. There is also a csv file (train_ship_segmentations_v2.csv) with image names and strings of "ship" pixels encoded in rle. 

#### Model
Aim of my model is to find parts of the image where ships are located
I used 1600 images (from ones that contain ships) to fit and evaluate my model.
