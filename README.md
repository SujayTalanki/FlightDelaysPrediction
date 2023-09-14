# DSC 148 Final Project (Winter 2023)
Team Members: Chester Kai Ni, Sujay Talanki

## Dataset
Kaggle Dataset: https://www.kaggle.com/datasets/heemalichaudhari/airlines-delay

Note that due to the uncompressed dataset being >200MB and exceeding the GitHub file size limit, a compressed zip folder containing the dataset is included in the repository. Furthermore, a .gitignore file is included to ignore the uncompressed dataset file, which should be stored directly in the repository folder locally as ./data/DelayedFlights.csv.

## Predictive Task
After performing EDA, we build a classification model with LightGBM to predict the delay duration for flights. We categorize flight delay duration into five groups (0-30 mins, 30-60 mins, 1-2 hrs, 2-3 hrs, and 3+ hrs). We tune our hyperparameters using GridSearchCV from the Scikit Learn library to achieve a final cross validation performance score of 0.953.
# FlightDelaysPrediction
# FlightDelaysPrediction
