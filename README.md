# Breast-Cancer
It is a python machine learning project to predict if the cancer is Malignant or benign. 

# Dataset
It uses the open source dataset provided by UCI machine learning repository.
http://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28diagnostic%29

# Understanding Dataset
The dataset provides us the mean, standard error and worst values for the 10 important features that are computed regarding the nucleus of each cell. The features are  radius (mean of distances from center to points on the perimeter), texture (standard deviation of gray-scale values), perimeter, area, smoothness (local variation in radius lengths), compactness (perimeter^2 / area - 1.0), concavity (severity of concave portions of the contour), concave points (number of concave portions of the contour), symmetry, fractal dimension ("coastline approximation" - 1).

# Model
The dataset was split in 3:1 ratio for train and test. The dataset was then scaled in the range of (-1,1) by using the sklearn library.
The scaled data was passed through the LogisticRegression model so that we can get the probabilities of the patient having a malignant or benign cancer.
The overall confusion score of the model was good even though a simple model was used.
