# neural-network-challenge-1

# Neural Networks

In this challenge we are to create a keras neural network model to predict if a student will repay on their loan.

## Workflow
1. Prepare the data for the neural network model.
    - create target dataframe (y) based on the credit_ranking
    - create feature dataframe (X) from original data, dropping the credit_ranking column
    - split the data into training and test dataframes
2. Compile and evaluate the neural network model using tensor flow
    - create 2 hidden and the output layer to the model
    - compile the model
    - fit the model
    - evaluate the models loss and accuracy
    - save and export the data to a keras file.
3. Predict the load repayment success using the keras model
    - load the model from the saved file
    - make the predictions using the loaded model
    - generate a classification report from the predictions using the test data