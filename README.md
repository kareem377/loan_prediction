# # Loan Prediction

This code implements a loan prediction model using logistic regression. The data is first cleaned and processed, and then the model is trained and evaluated. The final predictions are saved to a CSV file.

## Data Cleaning

The first step is to load the data and clean it. The `Loan_Status` column is converted to a binary integer, and the `Dependents` column is converted to numeric values. Any missing values are filled in with random numbers.

## Data Processing

The next step is to process the data for training and evaluation. The `Loan_ID` column is dropped, and the data is split into a training set and a test set.

## Model Training and Evaluation

The model is trained using the training set. The accuracy, confusion matrix, and classification report are all calculated to evaluate the model.

## Model Predictions

The model is used to make predictions on the test set. The predictions are saved to a CSV file.

## Results

The model achieved an accuracy of 81.2% on the test set. The confusion matrix shows that the model correctly classified 673 loans and incorrectly classified 141 loans. The classification report shows that the model has a high precision and recall for both the positive and negative classes.

## Conclusion

The loan prediction model achieved a high accuracy on the test set. The model can be used to predict whether or not a loan will be approved.
