# Autisum_Prediction
This project aims to develop a machine learning-based model to predict Autism Spectrum Disorder (ASD) in individuals by analyzing behavioral and demographic data
## On Given dataset which ML Models are perform good
*   Since your dataset has mixed numeric + categorical features, here are the best models:

1.   Tree-based models (Best Choice) :-
*  Random Forest(RF) / XGBoost
✅ Handle mixed data well, strong for tabular classification.

2.   Logistic Regression-LOR (Baseline Model) :-
*   Works as a quick baseline, but not as powerful as tree models.

3.   Support Vector Machine (SVM) :-
*  Can work, but slower on larger datasets.

4.   Train model separately then compare their performer and pick up best one  
5.   Otherwise combine model in single method by using ensemble (voting)
-------------------------------------------------------------------------------------------------------------------------------------------------
⚖️ Rule of thumb:
*   If both classes are roughly close (say 45% vs 55%), it’s balanced.
*   If one class is below ~30% (like here, 23%), it’s imbalanced.

Our out put column is imbalanced
*   class 0 dominate 73%
*   class 1 dominate 23%
### So here we use
*  Precision, Recall, F1-score
---------------------------------------------------------------------------------------------------------------------------------------------------
## In Health Care, Recall_score is often more important than F1_score 
*   Reacll focus on False Negative (FN) 
*   FN means (Actual : yes , But predict : No ) This is denger 
###Due to this. In this project i focus on to increses Recall_score
---------------------------------------------------------------------------------------------------------------------------------------------------
## Model Selection

*   I got best Recal_score with LOR, So i selected LOR model for this project

### IN LOR I got Accuracy of 84% means 84% model predict correctly and Recall_score is 87%
