# deep-learning-challenge

## Overview
This deep learning model analyzes funding for the charitable group Alphabet Soup. The models goal is to determine which application is most successful. 

## Results 
Data Preprocessing 
* My target variable was IS_SUCCESSFUL. This would determine if the funding was successful (1) or failed (0)
* My feature variable was all the other columns such as APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, etc. 
* The variables we removed were EIN and Name as they did not help with predicting our goal

Compiling, Training, and Evaluating the Model
* I worked with 111 neurons, 3 layer (80 for input layer, 30 for hidden layer, 1 for Output layer)
* 2 Activation Functions (ReLU & Sigmoid)
* I used the collaboration of neurons and layers because I did not want it to be too complex and didn't want to create a model that matches the training set too closely
* Unfortunately the models target performance was not reached

## Summary 
* Overall the deep learning model was able to achieve an accuracy of ~72%. This just fell short of its 75% goal. If I were to improve the model I would deploy more layers and other machine learning models. 
