🩺 Liver Cirrhosis Classification using Machine Learning
This project applies machine learning techniques to classify the stage of liver cirrhosis based on patient medical data. 
It uses a cleaned and preprocessed dataset with a Random Forest model to predict the disease stage, achieving improved accuracy through hypertuning using gridsearchCv.
📂 About the Dataset:
The dataset used in this project is sourced from a Mayo Clinic study on primary biliary cirrhosis (PBC) conducted between 1974 and 1984. 
It contains medical records of patients diagnosed with liver cirrhosis, including demographic data, clinical symptoms, and lab results. 
Key attributes include Age, Sex, Drug, Ascites, Edema, SGOT, Cholesterol, Albumin, and more, with the target variable being the histologic stage of the disease (1, 2, or 3). 
The original dataset has been manually cleaned, and synthetic samples were added to improve model performance. You can access the dataset here
<https://www.kaggle.com/datasets/aadarshvelu/liver-cirrhosis-stage-classification>.
-->Features :
Data Cleaning and Handling of Missing Values
Feature Engineering (e.g., converting age from days to years)
Label Encoding
Train/Test Split and Model Evaluation
Model Training using RandomForestClassifier
Hyperparameter Tuning for Better Accuracy
Evaluation using Accuracy Score and Classification Report
=====>> ACCURACY : 82 %
