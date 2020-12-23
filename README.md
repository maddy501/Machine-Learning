# Machine-Learning
It contains implementation of various Supervised and Unsupervised Machine Learning Algorithm using Sckit Learn Libraries: The folder heirarchy is as follows: 
- Clustering: Implementation of Kmeans CLustering using python SckitLearn libraries 
- Linear Regression: Implementation of Linear Regression Model + Logistic Regression Model + Regularised Models(Elastic Net & Lasso) + Hyperparameter tuning using           Grid Search CV + ROC curve and AUC for logostic model
- Machine Learning Pipelines: Implements ML pipeline which include filling in missing values, Scaling the columns and implementating a ML Model
- Random Forest: Implements Random Forest for both classification and Regression. Implement Ensemble Learning using Random Forest and Linear Regression
- SVM: Implements SVM classifier using python libraries 

 **Machine Learning Projects**: 
 
=> Clustering&PCA: Perform Unsupervised k means clustering to design an environment to predict a class/category from a dataset based on specific features of that class. However, all the features are not strong enough or in other words features not that much variance/uniqueness across the classes. So clustering model needs to be designed. Following steps were performed:
- Loading the dataset into a pandas dataframe
- Scaling of the dataset
- Seperating features from labels
- Implement K means Clustering 
- Plot Elbow Plot to find the actual number of classes in the dataset
- Write a function to calculate purity score of the clusters
- Implement  k-means clustering for different distance metrics using pyclusteting library and find purity score
- Find the best metrics based purity score
- Use selection criteria (ANOVA, Chi-squared) to select best three features and use them for K-Means clustering
- Implement PCA on the dataset
- Plot captured variance with respect to increasing latent dimensionality

=>Forcasting temperature based on yearly weather data: 
Environment and its changes are the most complex system.The dataset contains total 10 features. Each row contains an hourly record of weather status and the data was recorded for the time period between 2006 and 2016.This project implements Linear Regression to predict temperature and implement Logistic Regresion to predict class label for precipitation type.  Following steps were performed:
- Loading the dataset into a pandas dataframe
- Draw a heat map to find insignificant features for predicting temperature
- Remove insignificant features
- Seperating Features and Labels
- Divide data into Train and Test in 70/30 ratio
- Implement Linear Regression and calculate Accuracy
- Create a regularised Regression model by implementing Ridge Regression, Grid Search CV, kfold Cross validation and calculate accuracy
- Implement Logistic Regression to predict Precipitation Type Columns class label
- Discuss the test performance using precision, recall and confusion matrix




