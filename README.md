# Titanic-Machine-Learning-from-Disaster
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. This repository represent different machine learning algorithms that used to to classify "Titanic: Machine Learning from Disaste" dataset.

First of all we do some exploration and visualization of the dataset, this could found in [Features_Importance](Features_Importance.ipynb) 

# Algorithms:

  1- Support vector machine [SVM](SVM.ipynb), which contain the support vector machine code with three types of kernels: 
  
    * Linear kernel
    * Polynomial kernel
    * RBF kernel
  
  2- Gaussian Naive Bayes [Gaussian_Naive_Bayes](Gaussian_Naive_Bayes.ipynb)
  
  3- Logistic Regression [Logistic_Regression](Logistic_Regression.ipynb)
  
  4- Decision Tree [Decision_Tree](Decision_Tree.ipynb)
  
  5- Random Forest [Random_Forest](Random_Forest.ipynb), which contain the code of random forest algorithm with Grid search algorithm to        search for the best parameters to train the random forest algorithm.
  
  6- Gradient Boosting Classifier [Gradient_Boosting_Classifier](Gradient_Boosting.ipynb), which contain the code of gradient boosting          classifier with Grid search algorithm to search for the best parameters to train the gradient boosting classifier.
  
  7- Bagging Classifier [Bagging_Classifier](Bagging.ipynb), contain the Bagging code with Gaussian Naive Bayes and Decision tree                algorithm.
  
  8- AdaBoost Classifier [AdaBoost_Classifier](AdaBoost.ipynb), which contain the code of AdaBoost Classifier with Grid search algorithm to      search for the best parameters to train the AdaBoost Classifier.
  
  9- Voting Classifier [Voting_Classifier](Voting.ipynb), which contain the voting code of five algorithms:
  
    * Logistic Regression
    * SVM with Linear kernel
    * Gaussian Naive Bayes
    * AdaBoost
    * Random Forest
  

# Dataset:
  * You can find and download the dataset from the link below:
  
      https://www.kaggle.com/c/titanic/data
      

# Results:

  | Algorithm  | Accuracy Score | Precision | Recall | F1-Score|
  | ------------- | ------------- | ------------- | ------------- |------------- |
  | SVM (Linear)  | 80.25  | 74.11  | 72.81  | 73.45 |
  | SVM (Polynomial)  | 85.97  | 81.36  | 70.18  | 75.35 |
  | SVM (RBF)  | 86.98  | 80.84  | 67.84  | 73.77 |
  | Naive Bayes  | 80.02  | 69.35  | 78.07  | 73.45 |
  | Logistic Regression  | 81.14  | 75.15  | 72.51  | 73.81 |
  | Decision Tree  | 91.36  | 74.00  | 94.61  | 69.16 |
  | random Forest  | 83.39  | 80.98  | 72.22  | 76.35 |
  | Gradient Boosting  | 87.32  | 80.33  | 71.64  | 75.73 |
  | Bagging (Naive Bayes)  | 80.02  | 69.35  | 78.07  | 73.45 |
  | Bagging (Decision Tree)  | 86.20  | 83.11  | 71.93  | 77.12 |
  | AdaBoost  | 83.16  | 78.33  | 73.98  | 76.09 |
  | Voting  | 82.49  | 73.71  |  75.44 | 74.57 |
