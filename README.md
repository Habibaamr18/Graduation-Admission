# Graduation-Admission-Prediction
 The project goal is to assist students in estimating their chances of admission on universty(Masters). Based on several features such as GRE Score, TOEFL Score, University Rating, and more. Using ml techniques

# Dataset
Admission predict
it contains information about students and their chances of admission to graduate programs.(Supervised)
Key feaures:
1. GRE Scores ( out of 340 )
2. TOEFL Scores ( out of 120 )
3. University Rating ( out of 5 )
4. Statement of Purpose -(SOP) Strength ( out of 5 )
5. Letter of Recommendation-(LOR) Strength ( out of 5 )
6. Undergraduate GPA-CGPA ( out of 10 )
7. Research Experience ( either 0 or 1 )
8. Chance of Admit ( ranging from 0 to 1 ) Its the output(Target)


# Project Objectives
1. Analyze the relationship between student features and admission chances.
2. Build and evaluate multiple regression models to predict admission chances.
3. Identify the most important features influencing admission.

# Technologies Used
a. Programming Language:
   - Python

b. Libraries and Frameworks:
   1. Data Manipulation and Analysis:
     - Pandas, NumPy

   2. Visualization:
     - Matplotlib, Seaborn

   3. Machine Learning:
     - Scikit-learn (for preprocessing, model training, evaluation, and hyperparameter tuning)


# Machine Learning Models
1. Linear Regression
2. Ridge Regression
3. Decision Trees
4. Random Forest Regressor
5. Gradient Boosting Regressor
6. Support Vector Regressor (SVR)

# Evaluation Metrics:
Models were evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

# Results
1. Chance of admit distribution is almost normally distributed.
2. Students with research experience tend to score higher in CGPA than student who don’t.
3. CGPA and GRE score have dominant effect on chance of admit.
4. The group of people with and without experience is almost balanced.
5. GRE and TOFEL scores seem to havelinear and positive relation.
6. Three models have agreed on CGPA to be the dominant feature, followed by GRE then TOFEL score.
7. All trained models show an approximateperformance.
