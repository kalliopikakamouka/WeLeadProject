# 🚗 Fuel Efficiency Prediction with Machine Learning 🔍📊
##📌 Project Overview<br/>
This project is part of the WE LEAD - Data Science & Business Intelligence Bootcamp and focuses on predicting city-cycle fuel consumption (MPG) for cars. Given a dataset with car attributes, our task was to classify fuel efficiency into low, medium, and high categories.<br/>

By leveraging machine learning, data preprocessing, and feature engineering, this project aims to develop a predictive model that can assist car rental companies in making informed fleet updates.<br/>
##🏗 Project Pipeline<br/>
###🔎 1. Exploratory Data Analysis (EDA)<br/>
- Investigated dataset structure and characteristics<br/>
- Handled missing values, inconsistencies, and feature distributions<br/>
- Visualized key relationships (e.g., correlation between weight & MPG)<br/>
###🛠 2. Data Preprocessing<br/>
- Cleaned and transformed the dataset for model compatibility<br/>
- Encoded categorical variables<br/>
- Scaled numerical features for better model performance<br/>
- Addressed outliers and missing values<br/>
###🤖 3. Machine Learning Models<br/>
We tested multiple classification algorithms to determine the best performer:<br/>

- Logistic Regression<br/>
- Decision Tree 🌳<br/>
- Random Forest 🌲🌲<br/>
- Support Vector Machine (SVM)<br/>
- K-Nearest Neighbors (KNN)<br/>
🔹 SMOTE (Synthetic Minority Over-sampling Technique) was applied to balance the dataset<br/>
🔹 Stratified K-Fold Cross-Validation was used to ensure robust performance evaluation<br/>

###🎯 4. Model Evaluation & Fine-Tuning<br/>
- Measured accuracy, precision, recall, and F1-score<br/>
- Compared model performance using cross-validation results<br/>
- Selected the best classifier based on performance metrics<br/>
###🚀 5. Deployment with Gradio<br/>
- Built a user-friendly Gradio interface for real-time predictions<br/>
- Allows users to input car attributes and receive fuel efficiency predictions<br/>
- Saves prediction history for future analysis<br/>

###📂 Project Structure<br/>
📁 data/ - Contains the original and processed datasets<br/>
📁 notebooks/ - Jupyter notebooks for EDA, preprocessing, and modeling<br/>
📁 models/ - Saved trained models and scalers<br/>
📁 app/ - Gradio web app for interactive predictions<br/>
📜 README.md - Project documentation<br/>
💾 requirements.txt - Required Python dependencies<br/>
