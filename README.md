# Breast-Cancer-Detection
This machine learning model acts as a binary classifier for cancer cells being benign or malignant.The dataset used is the Breast Cancer Wisconsin (Diagnostic) Data Set.Here we have trained three models based on KNN(K Nearest Neighbors),SVM(Support Vector Machines) and Logistic Regression.Further we compare the three models based on their recall scores.

## Conclusion
On comparing the three models based on their recall scores we see that SVM and Logistic Regression algorithms stand way better than KNN.Also on comparing the three models using ROC-AUC score we get to see that SVM and Logistic Regression Models ouperform the KNN Model.

|Algorithm            |Recall Score |ROC-AUC Score |
|:-------------------:|------------:|:------------:|
|Logistic Regression  | 	0.936170  |    0.99      |
|KNN                  |0.893617     |   0.97       |
|SVM                  | 	0.957447  |     1.00     |

