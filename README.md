# Sleep_Health_Lifestyle_Analysis
📌 Project Overview
Sleep plays a crucial role in physical and mental well-being, yet it is often affected by lifestyle factors such as stress, physical activity, sleep duration, and BMI. Insomnia affects about one-third of the general population, making it the most common sleep disorder in the United States.

This project focuses on predicting sleep disorders based on lifestyle data. It integrates Health Data Science, Predictive Analytics, and Lifestyle Research to bridge the gap between research and practical healthcare applications.

📊 Dataset
Source: Kaggle Sleep Health & Lifestyle Dataset
Size: 400 records, 13 attributes
Key Features:
Sleep Duration (hours): Total sleep per day
Sleep Quality: A subjective rating of sleep
Physical Activity Levels: Frequency/intensity of exercise
Stress Levels: Measured on a scale indicating daily stress
BMI Category: Underweight, normal, overweight, or obese
Daily Steps: Number of steps taken per day
Sleep Disorders: (None, Insomnia, Sleep Apnea)
⚙️ Methodology & Workflow

1️⃣ Data Preprocessing
Loading the Dataset: Importing and preparing the dataset for analysis.
Data Cleaning: Handling missing values, inconsistencies, and outliers.
Feature Selection: Removing unnecessary features to reduce overfitting.

2️⃣ Statistical Analysis
Summarizing numerical variables (mean, median, standard deviation).

3️⃣ Exploratory Data Analysis (EDA)
Distribution of Sleep Disorders across different occupations (Manual Labor, Office Worker, Retired, Student).
Violin Plot: Physical activity levels vs. Sleep disorders.
Heatmap: Correlation between age, blood pressure, stress, and health metrics.

4️⃣ Machine Learning Models
Objective: Evaluate multiple classification models to predict sleep disorders.
Feature Importance Analysis: Identifying the most influential lifestyle factors.
Models Tested:
Random Forest (Best Performing Model)
Decision Tree
Logistic Regression
Hyperparameter Tuning: Optimizing model performance.

📈 Results & Insights
✅ Stress levels and sleep disorders showed a strong correlation.
✅ Students experienced the highest stress, leading to poor sleep health.
✅ Physically active individuals had better sleep quality.
✅ Random Forest was the best-performing model for sleep disorder prediction.

📚 Technologies Used
✅ Python 🐍 (pandas, numpy, seaborn, matplotlib, scikit-learn)
✅ Machine Learning 🤖 (Random Forest, Logistic Regression, Decision Tree)
✅ Jupyter Notebook 📒 (for data analysis and visualization)

🔮 Future Applications in Healthcare
Medical Diagnosis 🏥 – Integrating predictive models into healthcare for diagnosing sleep disorders.
Wearable Devices ⌚ – AI-powered smartwatches and fitness trackers for sleep monitoring.
Mobile Health Apps 📱 – Personalized recommendations for better sleep.
Public Health Awareness 🏛️ – Data-driven campaigns promoting sleep health.
