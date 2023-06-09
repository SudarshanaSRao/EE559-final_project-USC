# Exploring Correlation-Driven Feature Selection for Mushroom Classification

Final Machine Learning Project for USC EE-559 (Machine Learning I: Supervised Methods)

## Repository rundown

### Objective
This project aims to analyze the effect of different feature engineering and dimensionality adjustment techniques (performed on the mushroom dataset) on the performance of various Machine Learning models. The mushroom dataset is a collection of 173 different species of 61,069 mushrooms. The dataset contains 15 features including a class labels column which indicates whether the mushroom is poisonous or edible. The dataset has to be pre-processed as the features are made up of both numerical and categorical values. Pre-processing resulted in an increase in the number of features on a large scale, hence the features had to be engineered, and the dimensionality had to be reduced. Five Machine Learning models were implemented- Logistic Regression, Support Vector Machine, Gaussian Naive Bayes Classifier, Random Forest Classifier, and Multi-layer Perceptron. Cross-validation was performed on the models, and the optimal model was selected based on the best performance.

### Dataset information
The dataset folder contains two CSV files (2.47 MB): training and testing datasets. The datasets consist of numerical and categorical data. The CSV files consist of 15 features of 173 different species of mushrooms (61069 mushrooms). The 15 features (the first row in both CSV files contain the headings of 15 features) are cap diameter, cap shape, cap surface, cap color, does-bruise-or-bleed, gill attachment, gill spacing, gill color, stem height, stem width, stem color, has-ring, ring type, habitat, and season. The last column is the class label 'p' and 'e'. 'p' stands for poisonous class, and 'e' stands for edible class.
The dataset and more information about it can be accesssed [here](https://archive.ics.uci.edu/ml/datasets/Secondary+Mushroom+Dataset).

## Executing the code files
All files can be run as a standalone file. All the import statements are defined in the very first cell of each file. The dataset files should exist in the present working directory of the code files. 

1) *Trivial_system.ipynb* contains the trivial system which outputs the two class labels- 'p' \& 'e' at random (on the testing dataset) using the respective probabilities: $S_0 = \frac{N_0}{N}$ and $S_1 = \frac{N_1}{N}$; where $N$ is the number of rows present in the training dataset, and $N_i$ is the number of training data points belonging to the respective class label $S_i$.

2) *Baseline_system.ipynb* contains the Nearest Means Classifier model.

3) *Models.ipynb* contains feature engineered data and the five models- Logistic Regression, Support Vector Machine, Gaussian Naive Bayes Classifier, Multi-layer Perceptron, and Random Forest Classifier.  
