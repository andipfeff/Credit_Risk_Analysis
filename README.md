# Credit Risk Analysis

## Overview of the analysis

Using LendingClub's credit card dataset, six different machine learning models were trained and evaluated to figure out which model, if any, would be the best predictor of credit card risk. The models were built by resampling the dataset using the imbalanced-learn and scikit-learn Python libraries within Jupyter Notebooks.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

1. **Random Oversampling**
   - Balanced Accuracy Score: 65.7%
   - Precision and Recall Scores: <br />
![RandomOverSampler_Imbal_Class_Rpt](https://user-images.githubusercontent.com/90863226/150655146-4753c63b-157f-40c9-8cf4-f5f313a8f51c.png)


2. **SMOTE Oversampling**
   - Balanced Accuracy Score: 66.2%
   - Precision and Recall Scores: <br />
![SMOTEOverSampler_Imbal_Class_Rpt](https://user-images.githubusercontent.com/90863226/150655150-9ed4d245-a6e8-499b-9641-b0542c12a7cd.png)


3. **Cluster Centroids Undersampling**
   - Balanced Accuracy Score: 54.4%
   - Precision and Recall Scores: <br />
![ClusterCentroidsUnderSampler_Imbal_Class_Rpt](https://user-images.githubusercontent.com/90863226/150655160-314b66dc-d36f-4a42-a046-be5122276fea.png)


4. **SMOTEENN Combination Sampling**
   - Balanced Accuracy Score: 68.8%
   - Precision and Recall Scores: <br />
![SMOTEENNComboSampler_Imbal_Class_Rpt](https://user-images.githubusercontent.com/90863226/150655165-f44d7bba-27b3-49da-834e-1ec1171a4fbf.png)


5. **Balanced Random Forest Classifier**
   - Balanced Accuracy Score: 78.9%
   - Precision and Recall Scores: <br />
![BalRandForEns_Imbal_Class_Rpt](https://user-images.githubusercontent.com/90863226/150655173-5fc1d3e4-f159-4b8f-9d1d-ade2c2d5c34f.png)


6. **Easy Ensemble Classifier**
   - Balanced Accuracy Score: 93.2%
   - Precision and Recall Scores: <br />
![EasyEns_Imbal_Class_Rpt](https://user-images.githubusercontent.com/90863226/150655176-6db7a5e7-0863-4c84-9c43-7ca45414dee8.png)



##  Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.