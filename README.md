# Cardiovascular Disease Prediction 💚
Predictive model for cardiovascular disease using real patient data. Features include age, gender, height, weight, glucose levels, smoking, alcohol intake, and physical activity. The model helps identify patients at risk and supports early intervention.

Objective

The main goal is to predict the probability of a patient having cardiovascular disease based on their clinical characteristics and lifestyle habits using Machine Learning techniques.

Possible Applications

Assisting healthcare professionals in the early detection of cardiovascular diseases

Screening tools for clinics and hospitals

Research on risk factors related to cardiovascular diseases

Next Steps

Exploratory Data Analysis (EDA): to understand patterns and distributions

Preprocessing: cleaning, handling missing values, encoding categorical variables, and normalization

Model Training: Logistic Regression,

Model Evaluation: using metrics like accuracy, precision, recall, F1-score, and ROC curve

Deployment: creating a pipeline for predictions on new patients.

📌 Professor's Feedback

This project was evaluated by Prof. Alexandre William Camargo, who provided the following comments:

✅ Data preprocessing: Complete check of data types, missing values, and descriptive statistics. Correct conversion of the weight column to float and appropriate outlier treatment in height and weight using clip.

📊 Exploratory analysis: Relevant plots (cholesterol, glucose, physical activity vs. heart disease) accompanied by critical reflections. Additional hypotheses were raised (age, BMI, genetics, lifestyle habits), enriching the interpretation beyond the plots.

🔎 Correlation: Clear heatmap visualization with red gradient. Highlighted variables most related to heart disease, noting that there was no critical multicollinearity in the dataset.

⚙️ Modeling pipeline: Stratified split, imputation, standardization, and SMOTE were properly documented.

🤖 Applied model: Logistic Regression with coefficients and intercept presented. Metrics (accuracy, precision, recall, F1) were well discussed, with emphasis on the importance of recall in healthcare problems.

🧪 Final evaluation: Test metrics were close to training metrics (no overfitting), confusion matrix was presented, and possible improvements suggested (feature engineering, additional variables). The only missing element was the AUC-ROC curve.

📘 Conceptual clarity: Well-written explanations about logistic regression, showing both theoretical understanding and didactic communication.
