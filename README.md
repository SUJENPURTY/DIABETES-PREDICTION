# DIABETES-PREDICTION
🩺 Diabetes Prediction
This project implements a machine learning pipeline to predict the likelihood of diabetes in patients based on clinical and demographic measurements. The model is designed to support healthcare professionals with early risk assessment.

📂 Dataset
The dataset contains medical records of female patients, with each observation including:
 
 Feature                       Description                                                                 
 ------------------------------------------------------------------------------------------
 Pregnancies               Number of times pregnant                                                   
 Glucose                   Plasma glucose concentration (mg/dL)                                        
 BloodPressure             Diastolic blood pressure (mm Hg)                                            
 SkinThickness            Triceps skinfold thickness (mm)                                             
 Insulin                   2-Hour serum insulin (mu U/ml)                                              
 BMI                       Body mass index (weight in kg/(height in m)^2)                              
 DiabetesPedigreeFunction  Diabetes pedigree function (likelihood of diabetes based on family history) 
 Age                      Age in years                                                                
 Outcome                   Class label (0 = No diabetes, 1 = Diabetes) 

 
⚙️ Project Workflow

# Data Preprocessing

Handling missing or zero values in Glucose, BloodPressure, SkinThickness, Insulin, and BMI.

Normalizing and scaling numerical features.

Splitting the data into training and testing subsets.

# Exploratory Data Analysis (EDA)

Visualizing distributions of each feature.

Analyzing correlations between features and the outcome.

Assessing class imbalance.

# Model Training

Training multiple classifiers:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine

# Model Evaluation

ccuracy, Precision, Recall, F1-Score.

ROC Curve and AUC.

Confusion Matrix.

# Prediction

Generating predictions on unseen patient data.

Supporting user-provided input for testing individual cases.

# 🛠️ Technologies Used

Python

Pandas

NumPy

scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

# 🚀 How to Run

# Clone this repository:

git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction

# Install dependencies:

pip install -r requirements.txt

# Launch Jupyter Notebook:

Run all cells to preprocess data, train models, and evaluate performance.

📝 Results

The Random Forest classifier achieved an accuracy of ~85% and an AUC score of 0.90 on the test set.





























