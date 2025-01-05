# Kaggle-Datasets

About Dataset
The dataset contains data on factors influencing heart attack likelihood among youngsters in India (ages 18-35). It captures demographic, lifestyle, medical, and clinical test information. This rich dataset is designed to help explore the connections between these factors and heart attack risk in the young population.

Key Features
Demographics

Age, Gender, Region, Urban/Rural residence, Socioeconomic Status (SES).
Lifestyle Factors

Smoking and alcohol consumption, dietary preferences, physical activity, screen time, sleep duration.
Medical History

Family history of heart disease, diabetes, hypertension, cholesterol levels, body mass index (BMI), stress levels.
Clinical and Test Results

Blood pressure, resting heart rate, ECG results, chest pain type, maximum heart rate, exercise-induced angina, blood oxygen levels (SpO2%), triglyceride levels.
Target Variable

Heart Attack Likelihood (Yes/No).

Use Cases
Machine Learning for Risk Prediction

Train classification models (e.g., logistic regression, random forests, or neural networks) to predict heart attack likelihood.
Public Health Insights

Identify high-risk groups (e.g., sedentary individuals with a family history of heart disease) for targeted interventions.
Lifestyle Recommendations

Study the impact of modifiable lifestyle factors like diet, exercise, and sleep on heart attack risk.
Regional and Socioeconomic Analysis

Explore the disparities in heart attack likelihood across regions and socioeconomic statuses in India.

Insights to Extract
Feature Interactions

Analyze non-linear relationships, such as how "Physical Activity" modifies the effect of "BMI" on heart attack risk.
Example: A high BMI may pose less risk for individuals with high physical activity.
Cluster Analysis

Perform clustering (e.g., K-Means, DBSCAN) to identify subgroups of individuals with similar risk profiles.
Latent Factors

Use dimensionality reduction techniques like PCA to uncover latent health patterns influencing heart attack risk.
Causal Relationships

Apply causal inference techniques to explore causation (e.g., does high stress directly lead to higher cholesterol levels?).
Regional Variance

Conduct geospatial analysis to study how environmental or cultural factors in different regions affect lifestyle and medical indicators.
Example Insights to Uncover
Stress and Sleep Interaction

Do high-stress individuals with less sleep show disproportionately higher risk for heart attacks?
Exercise-Induced Angina

Explore if exercise-induced angina correlates more with individuals having abnormal ECG results and high cholesterol.
Gender-Specific Risk Factors

Compare risk factor significance (e.g., smoking or BMI) between genders.
Dietary Impact

Assess the differential impact of vegetarian vs. non-vegetarian diets on triglyceride levels and heart attack risk.
Hidden Patterns

Discover rare but significant patterns (e.g., low SpO2 and normal BMI but high heart attack likelihood).
Starting Point for Insights
Correlation Analysis:
Check relationships between features and the target variable.

Predictive Modeling:
Implement a Random Forest or Gradient Boosting model and examine feature importance.

Time Series or Trends:
If extended to include time data, study trends in cholesterol and stress over time for individuals.


View less
Usability
10.00

License
MIT

Expected update frequency
Annually

Tags
Health Conditions
Heart Conditions
India
Public Health
Healthcare
heart_attack_youngsters_india.csv(1.47 MB)

10 of 26 columns

About this file

Add Suggestion
Demographics
Age: Captures the age range of individuals (18–35 years).
Gender: Distribution among males, females, and others.
Region: Geographical zones (e.g., North, South, East, West, etc.).
Urban/Rural: Differentiates between urban and rural populations.
Socioeconomic Status (SES): Low, middle, or high economic tiers.

Lifestyle Factors
Smoking and Alcohol Consumption: Frequency categories (e.g., never, occasionally, regularly).
Dietary Preferences: Vegetarian, non-vegetarian, and vegan choices.
Physical Activity: Levels (sedentary, moderate, high).
Screen Time: Hours spent on screens per day (digital exposure).
Sleep Duration: Average sleep hours per night.

Medical History
Family History of Heart Disease: Presence of hereditary risk.
Diabetes and Hypertension: Binary indicators of chronic conditions.
Cholesterol Levels: Total cholesterol in mg/dL.
BMI: Body mass index as an obesity metric.
Stress Levels: Low, medium, or high.

Clinical and Test Results
Blood Pressure (Sys/Dia): Systolic/diastolic pressure in mmHg.
Resting Heart Rate: Beats per minute at rest.
ECG Results: Normal or abnormal heart electrical activity.
Chest Pain Type: Categories of pain experienced (typical, atypical, etc.).
Maximum Heart Rate Achieved: During stress or exercise.
Exercise-Induced Angina: Whether angina is triggered by exertion.
Blood Oxygen Levels (SpO2%): Oxygen saturation in the bloodstream.
Triglyceride Levels: Fat content in the blood (mg/dL).

Target Variable
Heart Attack Likelihood: Binary target indicating the presence (Yes) or absence (No) of heart attack risk.
