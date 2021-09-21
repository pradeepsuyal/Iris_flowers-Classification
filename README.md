![iris](https://user-images.githubusercontent.com/86251750/133933923-f7aa078b-28ed-447f-a6f5-3b71df5dc09b.png)

Here I will be using the famous [Iris flower data set](https://en.wikipedia.org/wiki/Iris_flower_data_set).

The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by Sir Ronald Fisher in the 1936 as an example of discriminant analysis.

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor), so 150 total samples. Four features were measured from each sample: 
• The length and the width of the sepals and petals, in centimeters.

**Dataset**
---------------------
The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Iris). 

**About the dataset**
----------------------

The iris dataset contains measurements for 150 iris flowers from three different species.

The three classes in the Iris dataset:

• Iris-setosa (n=50)

• Iris-versicolor (n=50)

• Iris-virginica (n=50)

The four features of the Iris dataset:

•sepal length in cm

• sepal width in cm

• petal length in cm

• petal width in cm

**Model Accuracies:**
-------------------------
I have used five models for this classification dataset-

| Model        | Accuracy      | precision |  recall |  f1-score |
| -------------|:-------------:|----------:|--------:|----------:|
| SVM          | 0.98          | 0.98      |  0.98   |  0.98     |
| SVC with GridSearch | 0.97   | 0.96      |  0.98   |  0.97     |
| Logistic Regression | 0.98   | 0.98      |  0.98   |  0.99     |
|  KNN            |   0.93     | 0.94      |  0.84   |  0.94     |
| Random forest | 0.91         | 0.92      |  0.91   |  0.92     |
| Decission Tree | 0.89        | 0.91      |  0.90   |  0.90     |

we can see that svm and logistic regression performs best with the accuracy of 98% and also there is basically just one point that is too noisey to grab, which makes sense, we don't want to have an overfit model that would be able to grab that.

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)   ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)
