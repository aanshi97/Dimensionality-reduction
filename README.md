# Dimensionality reduction
In machine learning classification problems, there are often too many factors on the basis of which the final classification is done. These factors are basically variables called features. The higher the number of features, the harder it gets to visualize the training set and then work on it. Sometimes, most of these features are correlated, and hence redundant. This is where dimensionality reduction algorithms come into play. Dimensionality reduction is the process of reducing the number of random variables under consideration, by obtaining a set of principal variables. It can be divided into feature selection and feature extraction.

## There are two components of dimensionality reduction:
1)Feature selection: In this, we try to find a subset of the original set of variables, or 
features, to get a smaller subset which can be used to model the problem. It usually 
involves three ways:

Filter
Wrapper
Embedded

2)Feature extraction: This reduces the data in a high dimensional space to a lower dimension
 space, i.e. a space with lesser no. of dimensions.
 
 ## Methods of Dimensionality Reduction
 The various methods used for dimensionality reduction include:

1)Principal Component Analysis (PCA)
2)Linear Discriminant Analysis (LDA)
3)Generalized Discriminant Analysis (GDA)

## Advantages of Dimensionality Reduction
1)It helps in data compression, and hence reduced storage space.
2)It reduces computation time.
3)It also helps remove redundant features, if any.

## Disadvantages of Dimensionality Reduction
1)It may lead to some amount of data loss.
2)PCA tends to find linear correlations between variables, which is sometimes undesirable.
3)PCA fails in cases where mean and covariance are not enough to define datasets.
4)We may not know how many principal components to keep- in practice, some thumb rules are applied.
