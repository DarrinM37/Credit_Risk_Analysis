# Credit_Risk_Analysis


The machine learning algorithms used were:
RandomOverSampler
SMOTE
ClusterCentroids
SMOTEENN
BalancedRandomForestClassifier
EasyEnsembleClassifier

The reason for this analysis was to build and evaluate various machine learning models to evaluate individual customer credit risk. The dataset used to train the models was from LendingClub, "a peer-to-peer lending services company." After being cleaned, the dataset consisted of 68,817 entries, and was heavily unbalanced, with only 0.5% of entries being classified as "high-risk." 

<img width="293" alt="Target Value" src="https://user-images.githubusercontent.com/105955544/195242963-b78557cd-6a96-4f50-9249-f04622b5c5c0.png">

# Results

The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores below are a couple examples:

# Naive Randome Oversampling

<img width="745" alt="risk" src="https://user-images.githubusercontent.com/105955544/195243695-ce639ca1-544b-4fd9-a888-e19492f489aa.png">

# Smote

<img width="776" alt="risk2" src="https://user-images.githubusercontent.com/105955544/195243874-5c0aeba7-81cc-41d2-8dcf-2e948e8affa3.png">

# Summary

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
