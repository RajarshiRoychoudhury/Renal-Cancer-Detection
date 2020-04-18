# Renal-Cancer-Detection
**This project has 4 files :**
* Feature Ranking: which will take the original data and return the essential features
* 3 files on cancer_train_final_ab_features.ipnyb
* ab denotes the number of features used for classification.(28,33,29 features)

# Feature Ranking

**Procedure**


Preprocessing:
* The textual features are one-hot-encoded. The number of unique column values in the features are assigned numbers. Numeric data remained untouched.
Training
* Then each column was fed into a classifier, and the classification score was mapped with the feature name.
* After all the classification score was calculated, the scores were reverse sorted. The largest accuracy denoted best
* classification and hence was crucial for good classification. The features were printed according to their ranks

# Cancer detection
**Procedure**


Preprocessing
* The textual data was one-hot encoded. Numeric data remained as it is.
* The logarithmic values of the columns were taken as a form of normalisation(this ensured best accuracy amongst other preprocessing techniques like standard scalar)


Training
* Data obtained from preprocessing was sent into classifiers like svm, random forest, gradient boot classifier, decision tree with 5 folds cross validation.






