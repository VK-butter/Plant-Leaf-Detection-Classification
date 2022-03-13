# Plant-Leaf-Detection-Classification
 in a variety of images, I started by using the Image processing technique to detect the area of leaf . Then create features such as Leaf color, shape, texture values ​​to create a feature that classify which leaf images are diseased and not diseased

# Overview
 This project demonstrates how I handle with a dataset that has a varied background and unwanted objects that are not in the foreground of images. Then, when we get only the foreground of leaves that we want, their shape, color, and texture-based features are extracted from the processed image to classify 2 classes of leaves (healthy and diseased).
 //
(You could try using deep learning techniques to extract features instead, but in this project I'm only going to experiment with Image processing techniques.)

 A dataset was created using the extracted features to train and test the model. The model used was the Support Vector Machine Classifier, and it was able to classify with 90.00% accuracy.
 
 # Dataset
 The dataset used is [Yellow Vein Mosaic Disease](https://www.kaggle.com/manojgadde/yellow-vein-mosaic-disease) Okra datase has 2 classes of okra leaves, which are disease leaves and healthy leaves.
 
 # Dependencies
[Numpy](https://numpy.org/)

[OpenCV](https://opencv.org/)

[Matplotlib](https://matplotlib.org/)

[Pandas](https://pandas.pydata.org/)

[scikit-image](https://scikit-image.org/)

It is recommended to use [Anaconda Python 3.6 distribution](https://www.anaconda.com/) and using a `Jupyter Notebook`

# Project structure

