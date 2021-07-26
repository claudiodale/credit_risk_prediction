# credit_risk_prediction
ML classification task
the task is to predict whether a customer will default starting from three intial variables: age, income, loan.
I perform EDA and feature selection first and then I create several different models looking for the best one.

In creating the model I use a pipeline where I pass a column transformer and the algorithm. I then pass the pipeline to the GridsearchCV.

for each model I provide summary of results, ROC curve and visual representation of the decision boundary using the mlextend library.
I also compare at the end the different models using the Cochran's Q test to compare their accuracies and know if there is a model that is better than the others.

An overall accuracy of 92% is achieved and all the models look good. The accuracy is a significant improvement of what could be achieved by a naive model that predicts always the most popular class (there are 85% of 0's).
