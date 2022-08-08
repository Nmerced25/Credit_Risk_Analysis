# Credit_Risk_Analysis

# Purpose
  
  The goal of this assignment was to explain how a machine learning algorthim is used for data analytics. With the use of a dataset, training and test groups were created. Furthermore, other aspects such as logistic regression, decision trees, random forest and support vector machine algorithims were implemented. With these results, they were interpreted and compared which ultimately helped determined which algorithim would be best used for the scenario. Lastly, to improve model preformance, ensamble and resampling techniques were used.


# Results
  
  Down below are the images for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:
   
  Narrative Random Oversampling:
   ![image](https://user-images.githubusercontent.com/101299252/183328603-b7ec273a-b13e-41da-81f3-ee9a7fbf9bdc.png)

    -Balanced Accuracy: 0.6612700484668286
    -Precision: The precision is low for High-risk loans and is high for Low-risk loans.
    -Recall: High/Low risk = .66/.67
  
  SMOTE Oversampling
    ![image](https://user-images.githubusercontent.com/101299252/183328812-39dfdcb0-019d-40dd-9405-44cca6aecdc3.png)
   
      -Balanced Accuracy: 0.6303296388959394
      -Precision: The precision is low for High-risk loans and is high for Low-risk loans.
      -Recall: High/Low risk = .62/.64
   
 Combination Under-Over Sampling
    ![image](https://user-images.githubusercontent.com/101299252/183328919-ebb39a4a-a84e-47b1-b243-22b65a53f251.png)

      -Balanced Accuracy: 0.5173713090878325
      -Precision: The precision is low for High-risk loans and is high for Low-risk loans.
      -Recall: High/Low risk = .70/.57
      
 Balanced Random Forest Classifier
    ![image](https://user-images.githubusercontent.com/101299252/183329114-d0db0291-b996-466d-9d06-f00cfaefd3c4.png)

      -Balanced Accuracy: 0.7877672625306695
      -Precision: The precision is low for High-risk loans and is high for Low-risk loans.
      -Recall: High/Low risk = .67/.91
    
 Easy Ensamble AdaBoost Classifier
    ![image](https://user-images.githubusercontent.com/101299252/183329245-62b96be0-4643-4924-a1be-a425acad337e.png)
    
      -Balanced Accuracy: 0.925427358175101
      -Precision: The precision is low for High-risk loans and is high for Low-risk loans.
      -Recall: High/Low risk = .91/.94
      
# Summary
  
  When working with the balanced accuracy, having a result closest to 1 would provide the most accurate model in a scenario. This scale runs from a 0-1 and with this comparison within the credit card dataset, the AdaBoost Classifier showed to be the best option with a score of .93 for balanced accuracy. By comparison, the other models show to sit below a .8; with the similarities of percision within the appropriate range. Furthermore, the AdaBoost Classifier has the highest recall score which also sits on a scale from 0-1. With this results this machine learning model proves to be the best choice for any credit card analysis.
