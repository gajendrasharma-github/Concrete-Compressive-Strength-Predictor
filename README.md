# Concrete Compressive Strength Predictor

## Project Description
The goal of this project is to predict the compressive strength of concrete based on its composition. Accurate prediction of compressive strength is crucial for ensuring the quality and safety of concrete structures. This project aims to build a reliable model that can predict compressive strength using various features such as the quantities of cement, water, and other components.

In this project, we have undertaken a detailed analysis of a concrete dataset, which includes features related to the composition of concrete and the compressive strength as the target variable. The project involves exploratory data analysis (EDA), data preprocessing, feature engineering, and the application of machine learning models to predict compressive strength. 

### Steps Involved:
1. **Data Collection and Loading:**
   - The dataset contains features such as cement, water, coarse aggregate, fine aggregate, and others.

2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics were calculated to understand the basic characteristics of the data.
   - Univariate and bivariate analyses were performed to explore the distribution of individual features and their relationships with the target variable.

3. **Data Preprocessing:**
   - Outlier Treatment 
   - Data was normalized to ensure consistent scale across features.
   - Multicollinearity was checked using the Variance Inflation Factor (VIF).

5. **Feature Engineering:**
   - New features were derived to enhance the predictive power of the model.
     
6. **Model Building and Evaluation:**
   - Several machine learning models were trained and evaluated using metrics such as RMSE, MAE, and R².



## Business Interpretation
`1.` All the features are significant

`2.` The intercept being -16.4837, is absurd because negative compressive strength makes no sense.

`3.` One unit increase in Cem_Wat_ratio, increases the strength by 19 Mpa.

`4.` If the concrete ages by 1 day, there is increase in strength by .312 Mpa.

`5.` Adding a superplasticizer by 1 unit, increases the strength by 0.2879 MPa.
