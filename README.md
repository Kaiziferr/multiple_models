# Multiple Models
This repository contains different strategies for using multiple models.

## OneVsRest
The approach consists of transforming a multi-class classification problem into several binary classification problems by training a binary classifier for each class. To predict the class of a new instance, the probability or score of each classifier is calculated, and the class with the highest score is selected as the prediction
