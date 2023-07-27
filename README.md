# Heart-Disease-Prediction-using-Bio-Inspired-Algorithm
This repository contains the code and dataset for building and comparing various machine learning algorithms to predict heart disease. The project aims to analyze health-related attributes and determine the most accurate algorithm for heart disease prediction.

# Dataset
Age: The age of the patient.
Sex: The sex of the patient (1: male, 0: female).
Chest Pain Type (cp): A categorical feature indicating the type of chest pain experienced by the patient.
Resting Blood Pressure (trestbps): The patient's resting blood pressure.
Cholesterol (chol): The patient's cholesterol levels.
Fasting Blood Sugar (fbs): A flag indicating if the fasting blood sugar is higher than 120 mg/dl (1: true, 0: false).
Resting Electrocardiographic Results (restecg): Results of the resting electrocardiogram.
Maximum Heart Rate Achieved (thalach): The highest heart rate recorded during exercise.
Exercise-Induced Angina (exang): A flag indicating if exercise induced angina (chest pain) (1: yes, 0: no).
ST Depression Induced by Exercise (oldpeak): ST depression induced by exercise relative to rest.
Slope: The slope of the peak exercise ST segment.
Number of Major Vessels Colored by Fluoroscopy (ca): Number of major vessels colored by fluoroscopy.
Thalassemia (thal): A categorical feature indicating the type of thalassemia.
Class: The target variable indicating the presence or absence of heart disease (0: no heart disease, 1: heart disease).


# Algorithms
Genetic Algorithm (GA):
Genetic Algorithm is a nature-inspired optimization technique that mimics the process of natural selection and evolution. It is used here for feature selection.
The GeneticSelectionCV class from genetic_selection is employed for feature selection using a logistic regression classifier as the base estimator.
The algorithm optimizes the selection of the most relevant features to improve the accuracy of the predictive model.

Bat Algorithm (BA):
Bat Algorithm is another nature-inspired optimization algorithm that simulates the behavior of bats searching for prey using echolocation.
The BAT class from SwarmPackagePy is used to implement the Bat Algorithm.
In this case, it is applied to optimize the parameters of a Random Forest classifier.

Bee Algorithm (ABE):
Bee Algorithm is a bio-inspired optimization algorithm inspired by the foraging behavior of honeybees.
The BEE class from SwarmPackagePy is used to implement the Bee Algorithm.
Similar to the Bat Algorithm, it is applied to optimize the parameters of a Random Forest classifier.

# Setup and Usage
Clone this repository to your local machine.
Install Python 7.0.1 and the necesarry packages including matplotlib.
Run the Main.py file to perform data preprocessing, model training, evaluation and results.
When the GUI appears, click on upload files and give the csv dataset.
Click on the following buttons to preprocess data, get accuracy of algorithms and a comparison graph.
View the results and accuracy scores of each algorithm to determine the most accurate model.
