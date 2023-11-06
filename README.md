# Impurity-Prediction-in-Mined-Ore
As part of my coursework, me and my team of total 4 members were given a dataset (www.kaggle.com/edumagalhaes/quality-prediction-in-a-mining-process) containing information about a flotation plant,
which was specifically for iron ore mining. Our main goal was to use this dataset to predict how much impurity was in the ore 
concentrate. As this impurity was being measured every hour, if we could predict how much silica (impurity) was in the ore
concentrate, we could help the on-site engineers by giving them early information to take corrective actions in advance to reduce
impurity and to also help the environment by reducing the amount of ore that goes to tailings as we reduce silica in the ore concentrate.

The data cleaning was rather easy to-do, as we only had drop duplicate values. Then we plotted various attributes to interpret the data 
distribution and to check for any correlations, but there weren't any which were any significant. Thus the data was incredibly non-linear, 
to our surprise. We did a PCA on the attributes and then used tried and tested various models, from very basic Linear Regression, 
Decision Trees, Random Forest; and I personally made the model making use of Artificial Neural Network.

The Linear Regression failed as expected with an R2 value of only 15.10%. The ANN I deployed with 4 hidden layers, using ReLU activation
function yielded a Mean Squared Error of 0.1812 and an R2 Score of 0.8571, which was a significant improvement over everything done on this 
dataset by the Kaggle community at that point of time, their R2 value only being 42% at time of making this project.

This project was an incredible opportunity for me and my team members to use real industry data to generate a tangible model for such a 
convoluted non-linear dataset. It took everything we had learned to make this project endeavor a success, and it was and exhilarating experience.
