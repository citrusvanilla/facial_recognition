# Facial Recognition With PCA and SVM

> Full disclosure- the following code comes from the scikit-learn example of an implementation of facial recognition [here](http://scikit-learn.org/stable/auto_examples/applications/face_recognition.html).

This repository contains a Jupyter notebook for walking the user through the implementation of 'facial recognition' technology using Python and associated libraries.  The code uses Principal Components Analysis to reduce the dimensionality of the images, and a 'support vector machine' supervised learning model to classify predictions.

![alt text](http://i.imgur.com/qnJ5YvO.jpg)

## Goals

- importing and preprocess dataset
- perform PCA anaylsis for dimensionality reduction
- fit and optimize SVM over a range of parameters
- evaluate results quantitatively 
- evaluate results qualitatively

## Software and Library Requirements
* Python 2.7.11
* Jupyter Notebook 4.2.2
* Numpy 1.11.2
* SciPy 0.16.1
* scikit-image 0.12.3
* matplotlib 1.5.2

## Data

The dataset used in the example is a preprocessed excerpt of the ["Labeled Faces in the Wild"](http://vis-www.cs.umass.edu/lfw/), which can be downloaded in full here: [Full Download (233MB)](http://vis-www.cs.umass.edu/lfw/lfw-funneled.tgz).  Though the `fetch_lfw_people` function in the notebook makes use of the scikit-learn codebase to handle this dataset for you.

## Getting Up and Running

While in the `facial_recognition` directory, use the following command in your command line interface:

> `ipython notebook facial_recognition_walktrhrough.ipynb`
