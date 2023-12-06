# CARDEKHO-KAGGLE-CAR-PRICE-PREDICTION
## END TO END MACHONE LEARNING PROJECT ON CARDEKHO KAGGLE DATASET.
1. FEATURE ENGINEERING : features like car name and year are dropped instead a new feature no of used years = currentyear-bought year is used.
2. One hot encoding is done for the categorical features.
3. Ensembling Learning ,i.e Random Forest Classifier is used. Hence normalization or standardization is not used.
4. Randomized Serach is used for hyperparametr tuning as it is faster.
5. The following hyperparameters are tuned: n_estimators, max_features,max_depth,min_samples_split,min_samples_leaf.
6. Built an webapp using flask and Html and deployed the model via heroku.
