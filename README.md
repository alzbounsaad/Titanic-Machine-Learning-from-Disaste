# Titanic-Machine-Learning-from-Disaster
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. This repository represent different machine learning algorithms that used to to classify "Titanic: Machine Learning from Disaste" dataset.

First of all we do some exploration and visualization of the dataset, this could found in [Features_Importance](Features_Importance.ipynb) 

Algorithms:

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
  

Dataset:
  * You can find and download the dataset from the link below:
  
      https://www.kaggle.com/c/titanic/data
