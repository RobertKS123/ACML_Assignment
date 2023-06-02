# ACML_Assignment

//Robert
Setup:
Link to the data (for easy access):
https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection?datasetId=2580326&sortBy=voteCount 
Extract the data into the data folder.


I have set up the project to ignore all csv and zip files so that they won't be added to the github
They are normally to big so github blocks them

//Sean
I haven't done too much as of yet, but I think we should all agree on a few things first. Mainly how we are going to pre-process the data in order to prepare it to train the models. So far, I have only changed 'type' to a numerical variable and dropped 'nameDest' and 'origDest'.
If we look at the correlation matrix we can see that their is a significant correlation between these two features and the target.

One idea I have that I am struggling to implement is to combine the sender-receiver pairs into a numerical value that can uniquely idebtify pairs of transactors - whether they are the sender or the receiver.

Notebooks:
Data Visulization 
Logistic Regression
Desision Tree
Random Forest
Deep Neural Network

Each NoteBook:
Import Data 
Pre-prosses data
random data spilt
even data split
Add good comments
Try tuning hyper parameters document any tuning you do
Print and compare results:
 - Confusion Matrix
 - F1 - metrics 
 - Record the loss through each epoch and graph
 - print the best weight matrix

