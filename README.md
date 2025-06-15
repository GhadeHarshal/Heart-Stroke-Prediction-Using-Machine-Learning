# Heart-Stroke-Prediction-Using-Machine-Learning

This project reveals several important insights from both the data analysis and modeling stages. These insights help explain how machine learning can play a vital role in healthcare decision-making.

 1. Key Risk Factors Identified
Through exploratory data analysis and model interpretation, the following features were found to be strongly correlated with stroke risk:

Age: Stroke risk increases significantly with age, especially after 60.

Hypertension: Individuals with high blood pressure are more prone to stroke.

Heart Disease: A history of heart disease contributes notably to stroke probability.

Average Glucose Level: Higher glucose levels, often linked to diabetes, increase risk.

BMI: Elevated BMI shows a slight correlation with stroke, particularly in overweight individuals.

These insights match common medical understanding and validate the quality of the dataset.

 2. Model Performance & Interpretation
The Random Forest Classifier delivered the best balance between accuracy and interpretability.

It performed well on both training and test datasets with minimal overfitting due to its ensemble nature.

Feature importance ranking showed that age, average glucose level, and hypertension were the top 3 contributing factors.

Using cross-validation and metrics like precision, recall, and F1-score ensured a robust evaluation beyond accuracy.

 3. Data Imbalance Consideration
The dataset was slightly imbalanced, with stroke cases being much fewer than non-stroke.

To tackle this, methods like resampling or using class weights in model training were considered.

This helped in improving recall—crucial in healthcare scenarios where false negatives (missing a stroke prediction) are more dangerous than false positives.

🖥 4. User Interface for Real-world Use
A simple GUI built with Tkinter allows users to input values like age, hypertension status, BMI, etc., and receive an instant prediction.

This interface makes the model accessible beyond data scientists and encourages community engagement or real-world integration.

 5. Real-World Impact
This tool can be a stepping stone toward early diagnosis and preventive healthcare.

It may be especially valuable in rural or low-resource areas where regular screening is not easily available.

While not a replacement for professional medical advice, it provides a decision-support system for both users and doctors.

* Technical Highlights
Implemented using Python, with libraries like:

Pandas, NumPy for data processing

Seaborn, Matplotlib for visualization

Scikit-learn for machine learning

Tkinter for GUI

Pickle for model serialization

Cleaned and prepared the dataset to improve model reliability and eliminate noise.

