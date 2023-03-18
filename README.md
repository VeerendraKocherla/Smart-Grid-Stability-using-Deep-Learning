# Smart-Grid-Stability

Problem Statement: Given the values of Response Time, Power Balance, Price Elasticity of Producer and 3 differnt consumers along with Maximal real part of the characteristic differential equation root (if positive, the system is linearly unstable) Model has to predict if the Grid is stable or not. 

Get the dataset at [Smart Grid Stability - kaggle](https://www.kaggle.com/datasets/pcbreviglieri/smart-grid-stability). <br />

Analysed the data using histograms and projected the data into 2 dimensional using Principal Component Analysis (PCA)  for further insights in the data.<br />

This notebook analyses the accuracy, precision, recall, f1score, confusion matrix of the models: <br />
1. Logistic Regression, <br />
2. XG Boost, <br />
3. Linear SVM, <br />
4. RBF Kernel SVM, <br />
5. A Neural Network with 1 input layer, a batch Norm, 2 hidden layers with ReLU activaton, a output layer with sigmoid activation. <br />
on the dataset. 
