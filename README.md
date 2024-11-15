*Coffee Classification with KNN* : 
This project uses the Coffee Quality Data (CQI) dataset from Kaggle to classify coffee quality based on various attributes. The classification is implemented using the K-Nearest Neighbors (KNN) algorithm.

*Project Objective* : 
The goal of this project is to build a machine learning model to classify coffee quality into different categories. By analyzing the features of coffee samples, the model predicts the quality, helping coffee producers and consumers make informed decisions.

*Table of Contents* : 
1. Introduction
2. Dataset
3. Project Workflow


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. *Introduction* : 
Coffee quality is influenced by various factors such as bean origin, processing methods, and sensory attributes like aroma and acidity. By leveraging machine learning, this project predicts coffee quality categories, aiding producers and distributors in optimizing their processes.


2. *Dataset* : 
The dataset used in this project is the Coffee Quality Data (CQI) from Kaggle. It contains multiple features related to coffee quality evaluations.

      *Key Features:*

        Numerical Features:
        Altitude Mean Meters
        Aroma
        Flavor
        Acidity
        Body
        Balance
        Uniformity
        Sweetness
        Total Cup Points
        
        Categorical Features:
        Country of Origin
        Variety

        Target Variable:
        Coffee quality classification (<=84 Normal coffee, >84 Special coffee)

3. *Project Workflow* : 
1. Exploratory Data Analysis (EDA)
Inspect the dataset for missing values and duplicates.
Visualize feature distributions and relationships using matplotlib and seaborn.
Understand the influence of individual features on coffee quality.
2. Data Preprocessing
Handling Missing Values: Impute or drop missing data.
Feature Scaling: Normalize numerical features for uniform scaling.
Encoding: Convert categorical features into numerical representations using techniques like One-Hot Encoding.
3. Model Training
20% for testing and 80% for training
4. Model Evaluation
Metrics used:
Accuracy
Precision
Recall
F1-Score
Visualized the confusion matrix for detailed performance insights.
