# Principal-Component-Analysis-Projects

This repository contains the projects I did using PCA - Principal Component Analysis

In this particular repository I have 2 notebooks. 
# 1."PCA Principal Component Analysis Manual Implementation.ipynb":-
Dataset - Breast cancer wisconsin (diagnostic) dataset

In this I have shown the manual implementation of the whole PCA process:-
1. Scaling the data using StandardScaler.
2. Calculating the Covariance matrix using the Numpy library.
3. Calculating the Eigenvalues & Eigenmatrix from the covariance matrix using the Numpy library.
4. Getting N Principal Components from N features space.
5. Choosing the right no of Principal Components to which the dimensionality reduction has to be performed on the original feature space.
6. Sorting the eigenvectors based off their associated eigenvalues and then choosing the top required no.
7. Finally projecting our original data onto that eigenvector.
Thereby completing the PCA process.

For this dataset as it was present in scikit learn already, so it had the target column as well, which i used to in the final plot as hue to show the effect of the Dimensionality reduction and a perfect seperation of the data into two different classes.

Finally I have listed out the benefits of using PCA.

# 2."Principal Component Analysis Scikit learn.ipynb"

In this notebook I have used the same dataset as above and demonstrated the whole process using Scikit-learn.
1. In this I have used the "n_components" and "variance explained" attributes of PCA to show how these two can be used to our benefit.
2. I have used the Variance explained attribute to create a plot of no of principal componenets vs % of variance explained, to visually see the effect of Dimensionality reduction and choose the best no of Principal components for our final model.
