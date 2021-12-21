# predicting_vc_with_neural_networks

The goal of this project is to test several deep learning neural network models in order to predict the success of 
venture capital investments.  

The analysis uses an Encoder, StandardScaler and train_test_split in order to preprocess the data.  
Three neural network models are then tested to see if anyone of these models does a better
job at predicting the success of the venture investment.  All 3 models developed are saved down to a separate folder.

## Technologies (pip list)
This project uses Python 3.7
Pandas 1.2.4
Jupyter lab 3.0.14
pyviz 2.1.0
hvplot 0.7.3
numpy 1.20.1
sklearn 0.24.1 (StandardScaler, train_test_split, OneHotEncoder)
imbalanced-learn 0.8.1
Tensorflow 2.7.0 (Dense, Sequential)

#Installation Guide
Make sure to install the following dependencies:

Python 
hvplot
numpy
sql
scikit-learn
imbalanced-learn

#Imported packages:
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder

#Results from the first model:
print("Original Model Results")

# Evaluate the model loss and accuracy metrics using the evaluate method and the test data
model_loss, model_accuracy = nn.evaluate(X_test_scaled, y_test, verbose =2)

# Display the model loss and accuracy results
print(f"Loss: {model_loss}, Accuracy: {model_accuracy}")
Original Model Results
268/268 - 0s - loss: 0.5569 - accuracy: 0.7251 - 113ms/epoch - 421us/step
Loss: 0.5568753480911255, Accuracy: 0.7251312136650085

#Usage
Clone the github repository to run this program in Jupyter Lab 
https://github.com/flyfishjay/predicting_vc_with_neural_networks


#License
GNU 

#Contributors 
Columbia Fintech Bootcamp
Jason Muenzen www.linkedin.com/in/jason-muenzen-mba-frm
