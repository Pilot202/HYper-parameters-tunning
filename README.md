
Hyperparameters tunning involves the adjusting the configuration of a model known as hyperparameters. This help to improve the accuracy of the model or to decrease the errors by finding the best hyperparameters combination.
Thet common methods are Gridsearch method, Random search methods and the more advance one Bayesian Optimization.

here are some common hyperparameters for various machine learning models:

1. **Linear Regression:**
   - No specific hyperparameters to tune in the traditional sense. The model is straightforward and doesn't have complex parameters to adjust.

2. **Logistic Regression:**
   - Regularization strength (C)
   - Penalty (L1 or L2)

3. **Decision Tree:**
   - Maximum depth of the tree
   - Minimum samples required to split a node
   - Minimum samples required at a leaf node
   - Criterion for splitting (e.g., Gini impurity or entropy)

4. **Random Forest:**
   - Number of trees in the forest
   - Maximum depth of the trees
   - Minimum samples required to split a node
   - Minimum samples required at a leaf node
   - Criterion for splitting

5. **K-Nearest Neighbors (KNN):**
   - Number of neighbors (K)
   - Distance metric (e.g., Euclidean, Manhattan)

6. **K-Means:**
   - Number of clusters (K)
   - Initialization method (e.g., random or k-means++)

7. **Naive Bayes:**
   - There are usually no hyperparameters to fine-tune in a basic Naive Bayes model. However, variations like Gaussian Naive Bayes might have smoothing parameters.

8. **Support Vector Machine (SVM):**
   - Regularization parameter (C)
   - Kernel type (linear, polynomial, radial basis function, etc.)
   - Kernel-specific parameters (e.g., degree for polynomial kernel, gamma for radial basis function kernel)

The optimal hyperparameter values depend on the specific dataset and problem at hand. Grid search or random search methods are often used to efficiently explore the hyperparameter space and find the best combination.

The Notebook contain the Implementation of GRIDSEARCH and RANDOMSEARCH method.
