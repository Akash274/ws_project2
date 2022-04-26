# ws_project2

## Deploying Machine Learning Model on Google Cloud Platform

Youtube: https://youtu.be/wjSxup3JQss

### Introduction

The project is a web application that classifies images of skin moles using machine learning models.
Implemented a AutoML which is applied for image analysis and processing.
The images are trained according to pixel values of the image and then classify them according to the label of the image.
The web application for the machine learning model accepts image input for skin moles and predicts skin mole in the image to be benign or malignant. 

### Machine Learning Model On Google Cloud 
The Artificially Intelligent Platform includes tools for uploading your trained machine learning model to the cloud and sending prediction requests to the model. We will save our trained model using the tools supplied by our machine learning framework to deploy it on an Artificially Intelligent Platform. This entails converting the data that reflects our trained model into a file that we can use for cloud prediction. The saved model is then uploaded to a Cloud Storage bucket, and a model resource is created on Artificially Intelligent Platform with the Cloud Storage path to our saved model specified. We will also be including custom code when we deploy our model to alter how it handles prediction requests.

### Vertex AI
It brings together the Google Cloud services for building ML under one, unified UI and API. In Vertex AI, you can now easily train and compare models using AutoML or custom code training and all your models are stored in one central model repository. These models can now be deployed to the same endpoints on Vertex AI.

### Tensor Flow 
Tensor Flow is an open-source library (where we use the software to modify, publish, etc) generally considered for large-scale machine learning projects, including numerical computation. With its tools that have been developed, it supports developers in its best way. What makes Tensor flow different is that it involves multiple levels of abstractions, so you can choose the right one depending on your needs. We can build and train models by using high-level APIs which makes it much easier. Another vital feature includes better flexibility, eager execution allows for immediate iteration and debugging as well. Tensor has a standard way of representing data. It is used vastly in the leading companies to detect objects at a large scale to improve performance, improve speed and reliability, and detect complex fraud patterns.

### AutoML 
AutoML uses machine learning to analyze the content of image data. You can use AutoML to train an ML model to classify image data or find objects in image data.
A classification model analyzes image data and returns a list of content categories that apply to the image. For example, you could train a model that classifies images as containing a cat or not containing a cat, or you could train a model to classify images of dogs by breed.
An object detection model analyzes your image data and returns annotations for all objects found in an image, consisting of a label and bounding box location for each object. For example, you could train a model to find the location of the cats in image data.


![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s1.png)
### Machine Learning Model Confusion Matrix
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s14.png)
### Create the project on google cloud platform
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s2.png)

### Upload the data to create the data set on google console
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/ss4.png)

### Sourced and Prepared the Dataset
For the dataset we used a set of images which contained a dataset of images of benign skin moles and malignant skin moles. 
There are two different sets of images for benign and malignant and each set contains around 1800 images of size (224x224). 
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/ss5.png)

### Console on Google Cloud Platform
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s2.png)


### Install Google Cloud Packages for Python
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/ss9.png)

### Create Service account and Download authentication keys

![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s3.png)

![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s4.png)
### Set the authentication keys to access the model
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s5.png)
### Bucket Creation


![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s6.png)

### Data Set creation
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s7.png)
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s8.png)
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s9.png)
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s10.png)

### Training Model
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s11.png)
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s12.png)


### After training the model create an endpoint to access the model

![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s15.png)

### Trained Machine Learning Model
 Trained the model (approximately 80% of data will be used for training the model)
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/model_score.png)

### Train the model through the uploaded data set
![](https://github.com/Akash274/ws_project2/blob/master/screenshots/ss10.png)

### Tested Machine Learning Model
Evaluated model accuracy (approximately 20% of data will be used for validating the prediction)

![](https://github.com/Akash274/ws_project2/blob/master/screenshots/s16.png)

## References
### Lisa Tagliaferri, “An Introduction to Machine Learning”
https://www.digitalocean.com/community/tutorials/an-introduction-to-machine-learning, Digital Ocean, September, 2017. 
### crossML engineering, “Google Cloud Platform (GCP) for Machine Learning & AI”, 
https://medium.com/crossml/google-cloud-platform-gcp-for-machine-learning-ai-36165b1767b0 
### S. Gupta, A. Panwar and K. Mishra, "Skin Disease Classification using Dermoscopy Images through Deep Feature Learning Models and Machine Learning Classifiers," IEEE EUROCON 2021 - 19th International Conference on Smart Technologies, 2021, pp. 170-174, doi: 10.1109/EUROCON52738.2021.9535552, 
https://ieeexplore.ieee.org/abstract/document/9535552 
### Manu Goyal1, Thomas Knackstedt2, Shaofeng Yan3, and Saeed Hassanpour4, “Artificial Intelligence-Based Image Classification for Diagnosis of Skin Cancer: Challenges and Opportunities” 
https://arxiv.org/ftp/arxiv/papers/1911/1911.11872.pdf 
### Google AI Platform Machine Learning Solutions overview, 
https://cloud.google.com/ai-platform/docs/ml-solutions-overview 
### Tensor Flow
https://www.tensorflow.org/
### Google VertexAI 
https://cloud.google.com/vertex-ai
### Google AutoML
https://cloud.google.com/automl
### Google Cloud Storage Bucket
https://cloud.google.com/storage/docs/creating-buckets
