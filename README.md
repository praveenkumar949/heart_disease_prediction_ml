# Heart Disease Prediction Using machine learning models
Heart disease is one of the leading causes of death globally. This project aims to build machine learning models that can predict the presence of heart disease based on various health metrics, assisting in early diagnosis and effective treatment.

## Objectives
- Analyze and visualize a heart disease dataset.
- Build predictive models using machine learning algorithms.
- Evaluate model performance and compare accuracies.

## Dataset
The dataset used for this project is a CSV file containing health attributes associated with heart disease. Key features include:
- Age
- Cholesterol level
- Maximum heart rate
- Other relevant health metrics
 
The target variable indicates the presence of heart disease (1: Present, 0: Not Present).
## Dataset Exploration
- Shape: 303 rows and 14 columns.
- Missing Values: No missing values in the dataset.
- Data Types: Contains numerical features and a target variable.
## Exploratory Data Analysis (EDA)
- Distribution of Target Variable: Count plot of heart disease presence in the dataset.
- Feature Correlation Heatmap: Shows relationships between features to identify patterns.
- Histograms: Distributions of each feature.
- Pairplot: Displays relationships between selected features with respect to the target variable.
- Boxplot: Visualizes age distribution across target variable categories.
## Data Preprocessing
- Feature Selection: Target variable separated from features.
- Train-Test Split: Dataset divided into training (80%) and testing (20%) sets.
- Feature Scaling: Used StandardScaler to standardize features for improved model performance.
## Models Implemented
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
## Results
| Model                   | Accuracy (%) |
|-------------------------|--------------|
| Logistic Regression     | 85           |
| Random Forest           | 84           |
| Support Vector Machine  | 87           |  

![Screenshot 2024-11-09 133710](https://github.com/user-attachments/assets/4cc4f3fd-9174-404d-94bb-feb297f133cf)
## Model Training and Evaluation
Each model was trained on the training set, and predictions were made on the testing set. Accuracy and classification reports were generated to assess model performance.  
**Code Link:** https://colab.research.google.com/drive/16aX7LxONMXHn-vKUlb1eTwJAJGgBsLSd?usp=sharing
