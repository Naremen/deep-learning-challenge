# deep-learning-challenge

# Introduction 
    -In this challenge, the goal is to create a model that can predict whether applicants will be successful if funded by Alphabet Soup.
    -You will be given a CSV containing more than 34,000 organizations that have recieved funding from Alphabet Soup over the years.

# Processing the Data
    -To start you will need to read in the charity data to a Pandas Dataframe.
    -After the dataset is read in, drop the EIN and Name columns.
    -You will then need to determine the numbe of unique values for each column and for the ones with 10 or more unique values, pick a number of data points for each unique value. The number of data points you pick will be the cutoff point to bin "rare" categorical variables together in a new value.
    -You will then need to split the preprocessed data into a feature array and target array. These arrays will be used to split the data into training and testing datasets.

# Compile, Train, and Evaluate the Model
    -You will need to design a neural network, or deep learning model to create a binary classification model that can predict if an Alphabet Soup funded organization will be successful based on features in the dataset.
    -You will need to create hidden layers, check the structure of the model, compile and train the model, and create a callback that saves the model's weight every five epochs.

# Optimize the Model
    -Finally you will need to optimize the model to achieve a target predictive accuracy higher that 75%.
    -This could be anything from dropping more or fewer columns, or using different activation functions for the hidden layers.

# Write a Report on the Neural Network Model
    -Once you have optimized you model you will need to write a report on the performance of the deep learning model you created for Alphabet Soup.
    -Your report should highlight the overview, results, and summary of this project.
