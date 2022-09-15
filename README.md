# Credit_Risk_Analysis

## **Overview**
The purpose of this analysis was to apply machine learning in order to analyze credit risk of a subset of loan applications. Within this analysis, we utiized several analysis methods, including oversampling, undersampling and balaneced classifiers. 

## **Results**
**1. Naive Random Oversampling**
In our first model, naive random oversampling, we recieved a balanced accuracy score of 0.62. A snapshot of the full model is included below. 

!["Naive Random"](https://github.com/mhenson1989/Credit_Risk_Analysis/blob/main/Images/NaiveRandomOversampling.PNG)

**2. SMOTE Oversampling** 
Similar to our first random sampling model, the SMOTE oversampling method produced a balanced accuracy score of 0.65 and produced a similar overall classification report with very little distinct differences than the naive random oversampling model. A snapshot of the report is shown below.  

!["SMOTE"](https://github.com/mhenson1989/Credit_Risk_Analysis/blob/main/Images/SMOTEOversampling.PNG)

**3. Undersampling** 
Again, with the undersampling method, we see a similar balanced accuracy score to the two oversampling analyses. However, we see a larger margin of difference between the undersampling classification reports. 

!["Undersampling"](https://github.com/mhenson1989/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG)

**4. Combination (Over and Under) Sampling** 
Of the four methods so far, the combination sampling analysis produced the lowest balanced accuracy score. A snapshot of the overall report is listed below. 

!["Combo"](https://github.com/mhenson1989/Credit_Risk_Analysis/blob/main/Images/ComboSampling.PNG)

**5. Balanced Random Forest Classifier** 
We start to see a more promising balanced accuracy score with the Balanced Random Forest Classifier, with a score of 0.79 (rounded) - this is a significant increase on the first four methods. In this classification report, the pre and sub numbers at the high, low and avg. range are fairly comparable, but you see a larger margin within the other categories, compared to the other methods reports. 

!["Balanced Forest"](https://github.com/mhenson1989/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForest.PNG)

**6. Easy Ensemble Classifier** 
Finally, the Easy Ensemble Classifier methodology yields the highest balanced accuracy score with a 0.93. We also see this classification report showing overall higher numbers all around. 

!["Easy Ensemble"](https://github.com/mhenson1989/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble.PNG)

## **Summary**

I would recommend moving forward with the Easy Ensemble Classifier model, as it has the highest balanced accuracy score and therefore the smallest margin of error. 