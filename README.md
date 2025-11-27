# Single Cell RNA-seq Project

## Week 1 \& 2

* Understanding the main idea of single cell RNA-seq project
* Exploratory and descriptive analysis on the dataset
* Searching for solutions to handle dimensionality curse



# Update

* Performed gene selection based on a variance criteria with an arbitrary threshold of variance across cells of 0.5
* Performed a **log** preprocessing (better to have a robust variance of gene expression because less sensitive to outliers)
* Performed PCA on selected genes and kept the  first 30 components which accounts for 80% of the variablility in the data (plot of cumulated variance ratio across components)
* K-fold cross validation on several classifiers and visualisation of train-test balanced accuracy scores boxplots -> best result for logistic regression
* First submission with logistic regression for a score of 79%



## **TO DOS**



* Research documentation and insights available on High Variance Genes (HGVs) selection



* Implement hyper parameters search with Grid Search
