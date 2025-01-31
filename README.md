## Project Description: Next Word Prediction Using LSTM
#### Project Overview:

This project aims to develop a deep learning model for predicting the next word in a given sequence of words. The model is built using Long Short-Term Memory (LSTM) networks, which are well-suited for sequence prediction tasks. The project includes the following steps:

1- Data Collection: We use the text of Shakespeare's "Hamlet" as our dataset. This rich, complex text provides a good challenge for our model.

2- Data Preprocessing: The text data is tokenized, converted into sequences, and padded to ensure uniform input lengths. The sequences are then split into training and testing sets.

3- Model Building: An LSTM model is constructed with an embedding layer, two LSTM layers, and a dense output layer with a softmax activation function to predict the probability of the next word.

4- Model Training: The model is trained using the prepared sequences, with early stopping implemented to prevent overfitting. Early stopping monitors the validation loss and stops training when the loss stops improving.

5- Model Evaluation: The model is evaluated using a set of example sentences to test its ability to predict the next word accurately.

6- Deployment: A Streamlit web application is developed to allow users to input a sequence of words and get the predicted next word in real-time.

## How it works
This model is trained with `hamlet.txt` for predictiing the next word. Select one sentence from the hamlet.txt and enter the  input bar and the next word will be predicted as below example:
`[The Tragedie of Hamlet by William Shakespeare 1599]`

![How it works](./pictures/how_it_works.png)

## Runnig platform

This application is running on streamlit which is written in python. To test the application please click on [Streamlit App](https://lstmrnnnextwordprediction-p9yywanedxxhmgxwfu7cse.streamlit.app/)


