# Airline passengers prediction

# Objective 
Carry out Time series forecating on the number of International Airline Passengers in units of 1,000 for a given year and month by using various LSTM models. 
![image](https://github.com/ritikdhame/Airline_passengers_prediction/assets/7029092/b539a710-d214-444b-a923-8cd476075f4f)

# About the data 
The dataset contains :  Number of Air Passengers in units of 1,000 for a given year and month. The dataset spans from January 1949 to December 1960, covering a period of 12 years with a total of 144 observations.

# Requirements
To run the code, you need to install the following libraries:

- matplotlib
- Math 
- keras
- Scikit Learn 

# Algorithm 
- Single LSTM 
- Stacked LSTM 
- Bidirectional LSTM 
- Convolution LSTM 

# Methodology 
The code consists of 3 main parts:

- Data loading and visualization: This part uses os, matplotlib, Keras and  libraries to load, process the data. 
- Preprocessing: Involves reshaping and normalizing the data 
- Model building and training: This part using the keras libraries to build a single LSTM model, followed by Stacked LSTM model, Bidirectional LSTM model and Convolution LSTM model that can forecast the passenger for the airlines. 
- We plot the train and test RMSE scores for each case and also compare the scores across the different models towards the end. 

The code requires the following dataset from Kaggle: https://www.kaggle.com/datasets/rakannimer/air-passengers?resource=download

# Procedure
You can install them using pip or conda commands.
To run the code, you need to execute the following steps:

1. Import the required libraries.
2. Load and play the audio clips using os and IPython.display.
3. Define the layer parameters and in the case of convolution flattening the data.
4. Building and fitting the model with keras package.
5. Evaluate and visualize the model performance using metrics and plots.
The code is commented and documented for better understanding and readability.

# Results 
![image](https://github.com/ritikdhame/Airline_passengers_prediction/assets/7029092/3d606c0b-0c46-40e1-85e8-d601638fdc1a)
