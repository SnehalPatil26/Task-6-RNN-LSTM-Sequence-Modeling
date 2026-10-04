# Task 6 – Sequence Modeling using RNN and LSTM Networks

## Student Details

**Student Name:** Snehal Sahebrao Patil
**Student ID:** 5146294
**Roll No.:** 34
**College:** B.K. Birla College of Arts, Science & Commerce, Kalyan

## Dataset

**IMDB Movie Reviews Dataset**

## Objective

To build and compare Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) models for sequence modeling and sentiment classification using the IMDB Movie Reviews Dataset.

## Description

This project focuses on sequence modeling using Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) networks. The IMDB Movie Reviews Dataset is used to classify movie reviews as positive or negative.

The project includes data preprocessing, sequence padding, RNN and LSTM model implementation, model training, performance evaluation, sample review prediction, and visualization of training and validation results.

The performance of RNN and LSTM models is compared using test accuracy and test loss. The project also demonstrates how LSTM networks are designed to handle long-term dependencies in sequential data more effectively than basic RNNs.

## Approach

* Load the IMDB Movie Reviews Dataset
* Preprocess and encode the review sequences
* Pad sequences to a fixed length
* Build and train an RNN model
* Build and train an LSTM model
* Evaluate both models using test accuracy and test loss
* Predict sentiment for sample movie reviews
* Visualize training and validation performance
* Compare RNN and LSTM results
* Analyze long-term dependency learning

## Models Used

### 1. Recurrent Neural Network (RNN)

A Simple RNN is used to process sequential movie review data and perform binary sentiment classification.

### 2. Long Short-Term Memory (LSTM)

An LSTM network is used to improve the learning of long-term dependencies in sequential data using memory cells and gates.

## Results

The RNN and LSTM models were evaluated on the IMDB test dataset using:

* Test Accuracy
* Test Loss
* Training and Validation Accuracy
* Training and Validation Loss
* Sample Review Predictions

The actual performance values are obtained from the model evaluation performed in Google Colab.

## Visualizations

The project includes:

* RNN Training and Validation Accuracy
* LSTM Training and Validation Accuracy
* RNN vs LSTM Test Accuracy
* RNN vs LSTM Training and Validation Loss
* Sample Review Prediction Scores

## Observations

* RNN can process sequential data for sentiment classification.
* RNN may face difficulty in retaining information from earlier parts of long sequences.
* LSTM uses memory cells and gates to control information flow.
* LSTM is designed to handle long-term dependencies more effectively than a basic RNN.
* Both models were compared using the same dataset and preprocessing steps.
* Model performance was evaluated using test accuracy and test loss.

## Conclusion

The project provided practical understanding of sequence preprocessing, RNN and LSTM implementation, sentiment classification, model evaluation, and comparison of recurrent neural network architectures.

## File

`Task_6_RNN_LSTM_Sequence_Modeling.ipynb`
