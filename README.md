# Airline passengers prediction

This project aims to build various LSTMmodels that can carry out forecasting on Air Passengers per month data.

The code consists of 3 main parts:

- Data loading and visualization: This part uses os, matplotlib, Keras and  libraries to load, process the data. 
- Preprocessing: Involves reshaping and normalizing the data 
- Model building and training: This part using the keras libraries to build a single LSTM model, followed by Stacked LSTM model, Bidirectional LSTM model and Convolution LSTM model that can forecast the passenger for the airlines. 
- We plot the train and test RMSE scores for each case and also compare the scores across the different models towards the end. 

The code requires the following dataset from Kaggle: https://www.kaggle.com/datasets/rakannimer/air-passengers?resource=download

The dataset contains :  Air Passengers per month data.

To run the code, you need to install the following libraries:

- matplotlib
- Math 
- keras
- Scikit Learn 

You can install them using pip or conda commands.

To run the code, you need to execute the following steps:

1. Import the required libraries.
2. Load and play the audio clips using os and IPython.display.
3. Define the layer parameters and in the case of convolution flattening the data.
4. Building and fitting the model with keras package.
5. Evaluate and visualize the model performance using metrics and plots.

The code is commented and documented for better understanding and readability.