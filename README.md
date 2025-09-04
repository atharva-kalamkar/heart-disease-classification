# heart-disease-classification
This project focuses on building an end-to-end machine learning pipeline to predict whether a patient is at risk of heart disease based on clinical and demographic data.
The workflow follows a typical end-to-end data science pipeline, from data exploration to model evaluation and optimization.

# 📋 Project Overview

The notebook walks through the following steps:

Problem Definition – Understand the challenge and goals.

Data Collection – Load and explore the dataset.

Evaluation – Define success metrics (targeting 95% accuracy).

Feature Understanding – Analyze and document dataset features.

Modeling – Train multiple machine learning models.

Experimentation – Tune hyperparameters and select the best model.

The dataset used comes from the UCI Machine Learning Repository
 and is also available on Kaggle
.

# 📊 Features
Feature	Description
age	Age in years
sex	Sex (1 = male, 0 = female)
cp	Chest pain type
trestbps	Resting blood pressure (mm Hg)
chol	Serum cholesterol (mg/dl)
fbs	Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
restecg	Resting electrocardiographic results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina (1 = yes, 0 = no)
oldpeak	ST depression induced by exercise
slope	Slope of peak exercise ST segment
ca	Number of major vessels colored by fluoroscopy
thal	3 = normal, 6 = fixed defect, 7 = reversible defect
target	Presence of heart disease (1 = yes, 0 = no)
🛠️ Tech Stack

# The following libraries and tools are used in this project:

Python 3.8+

NumPy – Numerical computations

Pandas – Data manipulation and analysis

Matplotlib – Data visualization

Scikit-learn – Machine learning models and evaluation

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest

Grid Search & Randomized Search for hyperparameter tuning

# Create and activate a virtual environment (recommended)

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows


# Install dependencies

pip install -r requirements.txt

▶️ Usage

Open Jupyter Notebook:

jupyter notebook


# Run the notebook:

Open end-to-end-heart-disease-classification.ipynb

Execute the cells step-by-step.

Alternatively, you can run it in Google Colab by uploading the notebook and dataset.

# 📈 Model Evaluation

The models are evaluated based on the following metrics:

Accuracy

Precision

Recall

F1 Score

# 🧪 Example Models Used

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest Classifier

GridSearchCV / RandomizedSearchCV for hyperparameter tuning
ROC Curve and AUC

The target goal is to achieve ≥95% accuracy.
