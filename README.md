# Predicting Drug Consumption
## Models
### Gateway Drug Model
This model is meant to find out if there is a connection between marijuana, alcohol, and hard drug use. It can be found in gateway_drug_model.ipynb. There are three different models, but the one we chose to be in our UI is the third model, an SVM. There is also a grid search for this SVM towards the end of the file.

To run this model, you can run the cells in the jupyter notebook from start to finish. If there is a dependency error, there is code at the very bottom of the notebook that can be run to install an external library that was used to plot the SVM.

## Unused Model
### Drugs Personality Model
This model is meant to find out if there is a connection between consumption of certain drugs with personality measurements. It can be found in drugs_personality_model.ipynb. These certain drugs were selected for this model: Alcohol, Amphet, Cannabis, Coke, Ecstacy, LSD, Meth, and Mushrooms. There are five different models: MLPRegression(Certain Drugs vs Personality Measurements), MLPRegression(Certain Drugs vs One Specific Personality Measurement), Linear Regression, SVR(kernel=rbf), and SVR(kernel=linear). Due to low accuracies from these models, the Drugs Personality Model cannot be used for prediction of a person's personality from their drug use.

## User Interface
description of how to get the UI up and running on your local machine
