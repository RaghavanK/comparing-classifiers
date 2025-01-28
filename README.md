# comparing-classifiers

## Business Objective
We need to find whether a client is going to subscribe to a term limit or not given certain data points

## Interpreting the models
- Given the amount of data SVC takes much longer to train the model
- While the regular methods takes least amount of time with relatively better accuracy
- Decision Tree Classifer found to performing better at a lower tree depth signifying the output heavily dependent on few parameters
- Since the data is imbalanced the KNN model tend to perform better with higher K value
- For logistic regression, with relatively lower hyperparameter value model can be prevented from overfitting and improve generalization to unseen data.
- Logistic regression and decision tree has better performance with less training times and with accuracy rates comparable to other models

## Findings
- Focusing on few important features like default, age, education etc can lead to much valuable customers.
- Clients with universtiy, highschool education tend to subscribe more
- Single users have better subscription rate. So concentration on the demographic will yield better results

## Next steps
- Try to reach out of the above mentioned demographics to gather more data to better tune the models
