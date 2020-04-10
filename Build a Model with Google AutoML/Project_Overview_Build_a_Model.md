Build a classification model to identify images of chest x-rays using Google AutoML.

# Project Overview

In the previous project, you created the instructions needed to build a labeled dataset that distinguishes between healthy and pneumonia x-ray images. This dataset would eventually be used to build a product that helps doctors quickly identify cases of pneumonia in children. Remember that the goals of this product are to:
	• help flag serious cases,
	• quickly identify healthy cases,
	• and, generally, act as a diagnostic aid for doctors.
  
In this project, we are going to take the next step and build the classification model that would serve as the backbone of this product. (Don't worry, there's no coding involved!) For this task, we will use Google AutoML, an automated machine learning tool that will allow us to build the model and host it in the cloud. In order to appreciate how training data impact models, we will build models with 4 variants of the dataset. This project is designed to test your ability to 
	1. build a model using Google's AutoML Vision platform, and 
	2. understand how properties of data impact performance of models. 
  
# The Data

We'll be using the same Kaggle chest x-ray dataset that we used in the previous project, except here, we'll skip the step of using Figure Eight's platform to label the data, and just use the original labels supplied with the data on Kaggle. 

Kaggle chest x-ray dataset: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

Udacity AI Product Manager Nanodegree Program: https://www.udacity.com/course/ai-product-manager-nanodegree--nd088
