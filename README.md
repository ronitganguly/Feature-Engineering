# Feature-Engineering

# Introduction


In this case study, we are given a dataset of patients who have suffered from Spinal Cord Injury (SCI). Now, post SCI, patients have a tendency of developing Central Neuropathic Pain. It has been recorded that almost 50% of such cases show symptoms of this pain. What more of a problem is, there is no cure but prevention. Early detection is required to provide with selective treatments because the treatment medication has strong side effects. Therefore, data science can play its role in predicting whether a patient will show such symptoms or not.  

We have to build a classifier on the data that have been given. The data have been taken from the patients who have either developed Central Neuropathic Pain or they have not, within 6 months post SCI. The sample size is 18 patients (with 10 readings each) where 10 patients have developed the pain while the remaining 8 patients have not. This method involved taking brain readings of the patients from 48 different locations of the brain(using electrodes) highlighting 9 features.  Moreover, the features were categorized into 2 groups : Eye opened and Eye closed. Our prediction algorithm at the end should be able to predict whether the patient will develop the pain.

# Objective: 
To build a classifier without unnecessary features. 
The data has more number of features which make it complicated to understand, and increase the chance of "overfitting". Therefore, our classifier, if developed on the raw data, may have poor performance on predicting new cases. Or at least, our data will be less complicated with probably reasonable performance (with fewer features), which explains that some features might be redundant or do not contribute much to the overall prediction. Therefore, this is a task of feature engineering.

# Please read the report named "Case 1 2487190G"
