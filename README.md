# IRIS_Flower_Classification

# Objective-
The goal of this project is to build a classification model that predicts the species of Iris flowers using sepal and petal measurements. The primary focus is on data preprocessing, feature selection, model building, and evaluation.

# Dataset-
**File Name** : IRIS.csv

**Description** : Contains 150 samples of iris flowers, with features like sepal length, sepal width, petal length, and petal width.

**Target Variable** : species 

**Project Structure**

**data/**: Contains the dataset used for training and evaluation.

**notebooks/**: Jupyter Notebook with EDA, visualization, and model development.

**models/**: Serialized models saved for reuse.

**src/**: Contains main scripts for preprocessing, training, and evaluating the model.

**requirements.txt**: List of dependencies.

# Steps to Run-

1. Clone the Repository
2. Install Dependencies:pip install -r requirements.txt
3. Run the Model: python src/main.py
4. Evaluate the Model: Results and model performance will be displayed in the console.

# Evaluation Metrics
  - Accuracy

  - Classification Report (Precision, Recall, F1-Score)

 -  Confusion Matrix

# Results-

 - The model achieved high accuracy using Random Forest Classifier.

 - Feature importance analysis highlights which features contribute the most to the classification.
