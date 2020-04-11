# Diamond Proce Predictor
It uses [diamonds dataset](https://www.kaggle.com/shivam2503/diamonds) from kaggle.
The preprossing included converting categorical columns to Ordinal values. I have used Map here, but will be using Label Encoder and also dropping columns which wouldn't have elp in predicting values.

Then created a RandomForestReggressor with 250 estimators to get a 99.279% accuracy on the whole dataset.

## Possible additions
I will try to create a small application where, a person can enter the features of the diamond and a possible price will be returned.

