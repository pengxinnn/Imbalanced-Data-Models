# Imbalanced-Data-Models

The success of any football match lies in the coaches and managers of soccer teams, since they make decisions for selecting players for matches, planning the strategy and instructing players on the pitch and they are responsible for holding the team together. However, the process of selecting players, deciding the best strategy and supporting players based on their own attributes is always very difficult in real life, and it is hard for humans to make objective decisions based on so many attributes. So in this report, we are going to design a decision-support tool that can aid coaches and managers' decision making process and lead to a successful outcome.

We are using the 'Football Events' dataset from Kaggle (https://www.kaggle.com/secareanualin/football-events), which contains 9074 games, 941009 events from soccer leagues: England, Spain, Germany, Italy, France from 2011/2012 season to 2016/2017 season.

The models we proposed and implemented for dealing with imbalanced dataset:
1. Logistic regression using "bodypart", "situation" (baseline model).
2. Resampling training dataset - undersample majority class (Variant 1 subvariant 1).
3. Resampling training dataset - oversample minority class (Variant 1 subvariant 2).
4. Resampling training dataset - oversample minority class + add prior correction for the bias term (Variant 1 subvariant 3).
5. Neural network (Variant 2).
6. Decision tree as the classifier (Variant 2 subvariant).
7. Random forest as the classifier (Variant 2 subvariant).
8. AdaBoost as the classifier (Variant 2 subvariant).
9. Gradient boosting as the classifier (Variant 2 subvariant).
10. KNN as the classifier (Variant 2 subvariant).
11. Add a latent variable for each player and each attempt (Variant 3).
