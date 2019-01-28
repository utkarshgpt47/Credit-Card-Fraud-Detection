# Credit Card Fraud Detection

Throughout the financial sector, machine learning algorithms are being developed to detect fraudulent transactions.  In this project, that is exactly what we are going to be doing as well.  Using a dataset of of nearly 28,500(1% of the original Data) credit card transactions and multiple unsupervised anomaly detection algorithms. The data is imbalanced, we are going to identify transactions with a high probability of being credit card fraud.  In this project, we will build and deploy the following two machine learning algorithms:

* Local Outlier Factor (LOF)
* Isolation Forest Algorithm

Furthermore, using metrics suchs as precision, recall, and F1-scores, we will investigate why the classification accuracy for these algorithms can be misleading.

In addition, we will explore the use of data visualization techniques common in data science, such as parameter histograms and correlation matrices, to gain a better understanding of the underlying distribution of data in our data set. Let's get started!  
  
* Local Outlier Factor (LOF) -  is a score that tells how likely a certain data point is an outlier/anomaly.The LOF of a point tells the density of this point compared to the density of its neighbors. If the density of a point is much smaller than the densities of its neighbors (LOF ≫1), the point is far from dense areas and, hence, an outlier.  

* Isolation Forest Algorithm - The algorithm is based on the fact that anomalies are data points that are few and different. As a result of these properties, anomalies are susceptible to a mechanism called isolation. Moreover, this method is an algorithm with a low linear time complexity and a small memory requirement. It builds a good performing model with a small number of trees using small sub-samples of fixed size, regardless of the size of a data set.  
  

### Metrices  

* Precision - is defined as the number of true positives divided by the number of true positives plus the number of false positives. False positives are cases the model incorrectly labels as positive that are actually negative.

* Recall - is the number of true positives divided by the number of true positives plus the number of false negatives.

* F1- Score -  is the harmonic mean of precision and recall.

![](https://cdn-images-1.medium.com/max/1400/1*6NkN_LINs2erxgVJ9rkpUA.png)
![](https://cdn-images-1.medium.com/max/800/1*UJxVqLnbSj42eRhasKeLOA.png)


[*Data Set for the project*](https://www.kaggle.com/mlg-ulb/creditcardfraud/downloads/creditcardfraud.zip/3) 

