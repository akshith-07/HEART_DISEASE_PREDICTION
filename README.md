# HEART DISEASE PREDICTION USING MACHINE LEARNING



## OVERVIEW   
 
  Heart related diseases or Cardiovascular Diseases (CVDs) are the main reason for a huge number of death in the world over the last fewdecades and has emerged as the most life-threatening disease, not only in India but in the whole world. So, there is a need of reliable,accurate and feasible system to diagnose such diseases in time for proper treatment. Machine Learning algorithms and techniques havebeen applied to various medical datasets to automate the analysis of large and complex data. Many researchers, in recent times, havebeen using several machine learning techniques to help the health care industry and the professionals in the diagnosis of heart relateddiseases. This paper presents a survey of various models based on such algorithms and techniques andanalyze their performance. Models based on supervised learning algorithms such as Support Vector Machines (SVM), K-Nearest Neighbour (KNN), NaïveBayes, DecisionTrees (DT), Random Forest (RF) and ensemble models are found very popular among the researchers. 
  
## OBJECTIVE     
 
The main aim of the project is to predict heart disease via three different supervised machine learning methods including: SVM, Logistic regression and the MLP Classifier . This project also aims to propose an effective technique for earlier detection of the heart disease so that a person can avoid the serious stage/conditon of the heart disease.
 
## LIBRARIES USED 

A Python library is a collection of related modules. It contains bundles of code that can be used repeatedly in different programs. It makes Python Programming simpler and convenient for the programmer. As we don’t need to write the same code again and again for different programs. Python libraries play a very vital role in fields of Machine Learning, Data Science, Data Visualization, etc.Python libraries that are used in the project are:
• Pandas
• gradio
• Numpy 
• Matplotlib

## MODULES DESCRIPTION  


### Dataset Collection:
This module includes data collection and understanding the data to study the patterns and trends which helps inprediction and evaluating theresults.Dataset description is given belowThis Diabetes dataset contains 800 records and 10 attributes.
Table 1. Dataset Information
Attributes Type
Number of Pregnancies N
Glucose Level N
 Blood Pressure N
Skin Thickness(mm) N
Insulin N
BMI N  
Age N

### Data Pre-processing:
This phase of model handles inconsistent data in order to get more accurate and precise results. This dataset containsmissing values. So we imputed missing values for few selected attributes like Glucose level, Blood Pressure, SkinThickness, BMI and Age because these attributes cannot have values zero. Then we scale the dataset to normalizeall values.

### Clustering:
In this phase, we have implemented K-means clustering on the dataset to classify each patient into either a diabeticor non-diabetic class. Before performing K-means clustering, highly correlated attributes were found which were,Glucose and Age. K-means clustering was performed on these two attributes. After implementation of this
clustering we got class labels (0 or 1) for each of our record.

### Model Building:
This is most important phase which includes model building for prediction of diabetes. In this we have implementedmachine learning algorithms for diabetes prediction. These algorithms include Support Vector Classifier,Logistic Regression, K-Nearest Neighbour, Gaussian Naïve Bayes,Bagging algorithm, Gradient Boost Classifier.In this,I have just implemented the MLP Classifier.

### Evaluation:
This is the final step of prediction model. Here, we evaluate the prediction results using various evaluation metricslike classification accuracy, confusion matrix and f1-score.Classification Accuracy- It is the ratio of number of correct predictions to the total number of input samples. 

 
# HAPPY LEARNING 
