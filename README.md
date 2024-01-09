# K-nearest-neighbors
## Customer Category Classification Using k-Nearest Neighbors (kNN)
This repository contains code for classifying customer categories using the k-Nearest Neighbors (kNN) algorithm. The dataset used for this analysis includes information about customers, such as region, tenure, age, marital status, address, income, education, employment status, retirement status, gender, residence, and customer category.

## Dataset
The dataset used is a tabular dataset with the following columns:

 - Region
 - Tenure
 - Age
 - Marital Status
 - Address
 - Income
 - Education Level (ed)
 - Employment Tenure (employ)
 - Retirement Status
 - Gender
 - Residence Status
 - Customer Category (custcat)

## k-Nearest Neighbors (kNN) Classification
The kNN algorithm is implemented to classify the customer category based on the features:

 - Region
 - Tenure
 - Age
 - Marital Status
 - Address
 - Income
 - Education Level
 - Employment Tenure
 - Retirement Status
 - Gender
 - Residence Status

## Data Preprocessing
Before applying the kNN algorithm, the data is split into training and testing sets (80% training, 20% testing). To address differences in the magnitude of values, the data is standardized.

## Model Training
The kNN algorithm is initially applied with a randomly chosen value of k (k=4). Subsequently, the code iterates through different values of k to find the optimal value that maximizes accuracy.

## Code Execution Environment
The code has been implemented using Python and executed in Google Colaboratory. Google Colaboratory provides a free and convenient platform for running Python code in a Jupyter notebook environment.

## Files in the Repository
knn.ipynb: Jupyter notebook containing the code for kNN classification.
teleCust1000t.csv: The dataset used for training and testing the kNN model.
README.md: This readme file.

## Dependencies
The following Python libraries are used in the implementation:

pandas
numpy
sklearn
