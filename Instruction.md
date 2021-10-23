Titanic dataset

* Explore: How does each feature relate to whether a person survives/alives? Do the EDA in more detail than usual and explain the results!
Splitting: 80-20, stratify: y, random_state = 0

Preprocessing:
    * Drop decks
    * Fill in the missing value using a simple imputer
    * One hot encoding: sex, alone
    * Ordinal encoding: class
    * Binary encoding: embark town

Model selection:
    * Evaluation metrics used: F1_score
    * Logre, KNN, DecisionTreeClassifier, RandomForestClassifier
    * Hyperparameter tuning of 2 models that you think is the best
    * Create a summary for the evaluation results and conclusions on which model is the best for the titanic dataset

If possible, use pipelines when necessary to avoid data leakage.