Breast Cancer Wisconsin (Diagnostic) Data Set
Predict whether the cancer is benign or malignant

About Dataset
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

**Project Overview**
This project aims to develop a machine learning model that can accurately detect and classify breast cancer into two categories: benign or malignant. 
The model is trained on a dataset of breast cancer images and uses various machine learning techniques to analyze the data and make predictions.

**Dataset**
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which contains 569 instances of breast cancer images,
each with 32 attributes (ID, diagnosis, and 30 real-valued input features). The dataset is divided into two classes: benign (357 instances) and malignant (212 instances).

**Data Analysis**
The data analysis step involves exploring the dataset to understand the distribution of the features and their relationships with each other. 
The analysis reveals that the features are correlated with each other, with radius, perimeter, and area having strong positive correlations.

**Machine Learning Steps**
The machine learning steps involve training and evaluating various models to classify the breast cancer images into benign or malignant categories.
The models used in this project include:

**Feature Scaling**: The features are scaled using the StandardScaler to have zero mean and unit variance.
**Removing Outliers:** The outliers are removed using the Isolation Forest algorithm to improve the model's performance.
**Model Training:** The models are trained using the training dataset, and their performance is evaluated using the testing dataset.
**Model Evaluation:** The models are evaluated using the F1 score, which is a measure of the model's accuracy.

**Results**
The results of the project show that the machine learning model can accurately classify breast cancer images into benign or malignant categories.
The model achieves an F1 score of 98.55%, which indicates that it can correctly classify most of the instances.

**Conclusion** 
In conclusion, this project demonstrates the use of machine learning techniques to detect and classify breast cancer into benign or malignant categories. 
The project highlights the importance of data analysis and preprocessing in improving the model's performance. 
The results of the project show that the machine learning model can be a useful tool in the diagnosis of breast cancer.

