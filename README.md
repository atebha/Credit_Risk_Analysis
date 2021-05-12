# Credit_Risk_Analysis

Purpose:

  To use machine learning models and algorithms to predict credit risk. A dataset form lenidng club was used for analysis and to trian the models. Two machine learning models were used and four algorithms. 

  ML Models:
    Balance Random Forest Classifier
    Easy Ensemble Classifier
    
  Alogrithms
    SMOTE - Over Sampler
    Random Over Sampler - Over Sampler
    Cluster Centroids - Under Sampler
    SMOTE Combo - Over Sampler & Under Sampler
    
Analysis:

  SMOTE: 
    - High Risk category had a 1% precision score with a recall of 63%.
    - Low Risk category had a 100% precision score with a recall of 69%.
    - Overall category had a 99% precision score with a recall of 69%. 
    
    ![resampling_SMOTE](https://user-images.githubusercontent.com/50600624/117899334-c3c32600-b27b-11eb-921c-fb9736756a83.PNG)

  Random Oversampling
    - High Risk category had a 1% precision score with a recall of 63%.
    - Low Risk category had a 100% precision score with a recall of 61%.
    - Overall category had a 99% precision score with a recall of 61%. 

    ![resampling_random_oversampling](https://user-images.githubusercontent.com/50600624/117899549-36340600-b27c-11eb-8b7f-86a772133c13.PNG)

  Cluster Centroids Undersampling
    - High Risk category had a 1% precision score with a recall of 68%.
    - Low Risk category had a 100% precision score with a recall of 41%.
    - Overall category had a 99% precision score with a recall of 41%.

    ![resampling_undersampling](https://user-images.githubusercontent.com/50600624/117899930-10f3c780-b27d-11eb-843b-1062d8962ed3.PNG)

  Combo Over/Undersampling
    - High Risk category had a 1% precision score with a recall of 72%.
    - Low Risk category had a 100% precision score with a recall of 57%.
    - Overall category had a 99% precision score with a recall of 57%.

    ![resample_combosampling](https://user-images.githubusercontent.com/50600624/117900233-a1caa300-b27d-11eb-8311-fceda9548b95.PNG)

  Balance Random Forest Classifier
    - High Risk category had a 3% precision score with a recall of 70%.
    - Low Risk category had a 100% precision score with a recall of 87%.
    - Overall category had a 99% precision score with a recall of 87%.

    ![balance_random_forest_classifier](https://user-images.githubusercontent.com/50600624/117900310-c888d980-b27d-11eb-92b6-daf39a0fcee1.PNG)


  Easy Ensemble Classifier
    - High Risk category had a 9% precision score with a recall of 92%.
    - Low Risk category had a 100% precision score with a recall of 94%.
    - Overall category had a 99% precision score with a recall of 94%.

    ![ensemble_adaboost_classifier](https://user-images.githubusercontent.com/50600624/117900341-d6d6f580-b27d-11eb-9571-1251763f1341.PNG)


Challenges:

  No major challeneges were experienced.
  
Summary:

  The use of different algorithms and Logistic Regressions did not have a statistically significant difference in performance. All the models were poor models for predicting credit risk. All the Algorithm models had a score 41-69. The Ml models had a better score from 87-94. Fine tuning and optimizing the AdaBoost Model would be best to do because it had the best preformance compared to the rest of the models ran. 
