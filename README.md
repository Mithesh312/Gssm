# Voting Classifier

A Voting Classifier is a machine learning model that trains on an ensemble of numerous models and predicts an output (class) 
based on their highest probability of chosen class as the output.

It simply aggregates the findings of each classifier passed into Voting Classifier and predicts the output class 
based on the highest majority of voting. The idea is instead of creating separate dedicated models and finding 
the accuracy for each them, we create a single model which trains by these models and predicts output based on their combined majority of voting for each output class.

Voting Classifier supports two types of votings.

Hard Voting: In hard voting, the predicted output class is a class with the highest majority of votes i.e the class which 
had the highest probability of being predicted by each of the classifiers.

Soft Voting: In soft voting, the output class is the prediction based on the average of probability given to that class.


For those interested in setting up cross validation, model ensembles, and voting classifiers, this notebook might be valuable.
