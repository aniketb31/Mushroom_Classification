# Mushroom_Classification
A study to classify mushrooms as edible or poisonous based on a certain set of features.

The source of dataset is 'Mushroom Classification' at the link: https://www.kaggle.com/uciml/mushroom-classification

The study intends to identify whether a particular species of mushroom is edible or poisonous, on the basis of a number of features. The dataset includes hypothetical instances of mushrooms along with their values for all the features and identification of them as either edible or poisonous.

The below analysis intends to identify the features which are most indicative of mushroom edibility. For this purpose, the below techniques will be employed:

1. Correlation Matrix
2. Extra Trees Classifier for feature importance
3. Detailed EDA on the identified features

Additionally, the analysis will identify the machine learning (ML) models which will perform best on the given dataset. The below ML models will analysed:
1. SGD Classifier
2. Logistic Regression
3. K Nearest Neighbors
4. SVC (Linear and RBF)
5. Decision Tree
6. Random Forest
The dataset will be split into train, test and validation sets. The models will be trained on train set and evaluated on validation set. The final model/s will give the results for test set.

The performance measures used are Accuracy, Precision and Recall. A study of this nature will be much more concerned with keeping the false negatives (identification of poisonous mushrooms as edible) as low as possible even at the cost of an increase in false positives (identification of edible mushrooms as poisonous). Hence, a high Recall will be much more important than a high Precision.

Thus, the final model/s will be shortlisted on the basis of their Accuracy and Recall.
