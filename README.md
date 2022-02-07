# Breast-Cancer-Prediction

# Description
The goal of the project was to use a dataset to predict Breast Cancer with the information available within the given dataset.

# Dataset Description
The dataset used in the final project was the the Breast Cancer Wisconsin (Diagnostic) Dataset. 
It consists of 596 rows and 32 columns. This dataset was obtained from the website Kaggle and is labelled as “clean”, as it has 
neither null values nor any values that differ to the expected type “numeric”. Therefore, no data cleaning has to be performed 
on the compilation and all of the rows and columns can be loaded directly into a dataframe provided that the header is skipped. The columns are:
•	id
•	diagnosis
•	radius_mean
•	texture_mean
•	perimeter_mean
•	area_mean
•	smoothness_mean
•	compactness_mean
•	concavity_mean
•	concave points_mean
•	symmetry_mean
•	fractal_dimension_mean
•	radius_se
•	texture_se
•	perimeter_se
•	area_se
•	smoothness_se
•	compactness_se
•	concavity_se
•	concave points_se
•	symmetry_se
•	fractal_dimension_se
•	radius_worst
•	texture_worst
•	perimeter_worst
•	area_worst
•	smoothness_worst
•	compactness_worst
•	concavity_worst
•	concave points_worst
•	symmetry_worst
•	fractal_dimension_worst

The features are therefore properties of tumours and tissues except for diagnosis, which would serve as the outcome to be predicted. 
Diagnosis is different from the other features in that it is on a binary format of ‘M’ or ‘B’ which stands for Malignant or Benign respectively.
