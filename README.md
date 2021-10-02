# Hardhat-Head-detection
Helmet Detection using Tensorflow's Object Detection API

After creating csv files for both train and test data, convert them into tfrecords.
file : convert_to_csv.ipynb

ref: https://github.com/TannerGilbert/Tensorflow-Object-Detection-API-Train-Model

file : convert_to_tfrecords.ipynb

Create a label_map for num of classes in the dataset
file: data/tf_label_map.pbtxt

Download the model and the model's configuration file for training.

Edit the configuration file based on the dataset.

Train, export and test the model:
file: training_on_images.ipynb




