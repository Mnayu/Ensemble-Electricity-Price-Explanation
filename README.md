# Ensemble-Electricity-Price-Explanation
Project for the Ensemble Learning Course at CentraleSupelec

The project is to predict Electricity prices using ensemble learning methods. The challenge is from QRT and the dataset can be found here: [QRT Challenge](https://challengedata.ens.fr/challenges/97/data)

The training dataset consists of 1494 observations capturing the daily price variation (target variable) of electricity in Germany and France, along with 35 explanatory features which involve weather quantitative measurements (temperature, rain, wind), energetic production (commodity price changes), and electricity use (consumption, exchanges between the two countries, import-export with the rest of Europe)

We went through following process to predict the electricity prices:

1. Data Preprocessing
2. Feature Selection
3. Model Selection: We tested following models:
   1. Random Forest
   2. Stacked Linear Regression with Decision Tree.
4. Model Evaluation: The evaluation metrics used are:
   1. Mean Absolute Error
   2. Mean Squared Error
