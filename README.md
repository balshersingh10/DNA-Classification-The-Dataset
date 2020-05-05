![DNA-Classification]()
# Classification of DNA Using Supervised Machine Learning Techniques
We obtained the DNA dataset from UCI repository and used Jupyter Notebook as the platform for the purpose of coding. Our methodology involves use of classification techniques like Support Vector Machine (SVM), K-Nearest Neighbor (K-NN) and many more.
## A. Feature Selection
Feature selection is finding the subset of original features by different approaches based on the information they provide, accuracy, prediction errors.
The features used in the project are:
- a (0-56) (eg: 0_a, 1_a, ..., 56_a)
- c (0-56) (eg: 0_a, 1_a, ..., 56_a)
- g (0-56) (eg: 0_a, 1_a, ..., 56_a)
- t (0-56) (eg: 0_a, 1_a, ..., 56_a)
- Class (0/1)
## B. Model Selection
* Nearest Neighbors
* SVC/SVM model with Linear kernel
* SVC/SVM model with RBF kernel
* SVC/SVM model with Sigmoid kernel
* SVC/SVM model with Polynomial kernel
* Naive Bayes
* AdaBoost
* Neural Net
* Random Forest
* Decision Tree
* Gaussian Process
## C. Training the models with Data
The data taken is from **https://archive.ics.uci.edu/ml/machine-learning-databases/molecular-biology/promoter-gene-sequences/promoters.data**
## D. Taining Data and Testing Data
80% of above data is training and 20% is testing data.
### Then the Class is predicted:
- + (1)
- - (0)
# Result =>
Accuracy :
* Nearest Neighbors - 86.36363636363636 %
* SVC/SVM model with Linear kernel - 90.90909090909091 %
* SVC/SVM model with RBF kernel - 90.90909090909091 %
* SVC/SVM model with Sigmoid kernel - 90.90909090909091 %
* SVC/SVM model with Polynomial kernel - 90.90909090909091 %
* Naive Bayes - 90.90909090909091 %
* AdaBoost - 81.81818181818182 %
* Neural Net - 95.45454545454546 %
* Random Forest - 68.18181818181818 %
* Decision Tree - 86.36363636363636 %
* Gaussian Process - 95.45454545454546 %

## Files included in repository are:
- **source.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **source.pdf(Just a pdf print of jupyter notebook)**  <br />
