# Factors Affecting Appliance’s Energy Consumption

## 📌 Problem Statement
Household energy consumption varies based on environmental conditions, appliance usage patterns, and temporal factors such as date and time.
This project investigates:
How accurately can machine learning models predict appliance energy consumption using real-world sensor data?
Which indoor and outdoor environmental factors most influence energy usage?
Do ensemble models (e.g., Random Forest) outperform traditional regression approaches?
How can we build a predictive model that generalizes well without overfitting?

## 📂 Dataset
- Source: UCI Machine Learning Repository
- Size: 19k+ records
- Key features: Features for Temperature and Humidity values for various rooms within the house, Hour, Energy consumption of lights 

## 🔍 Approach
- Data cleaning
- Exploratory data analysis
- Feature engineering
- Machine Learning Modeling

## 🤖 Model
- Linear Regression and Random Forest Regressor
- R2-score, RMSE, MAE
- Achieved 75% accuracy with the Random Forest Regressor model with hyper-parameter tuning

## 📊 Key Insights
- The time of the day, and the temperature and humidity conditions in the room along with the usage of lighting 
appliances were found to have the highest impact on energy consumption.
- The Ensemble Random Forest Regressor model offers far better performance than the traditional Linear Regression model as it is not able to uncover the non-linearities in data.
- Feature engineering the variable of ‘date’ proved to be valuable for the accuracy of the final model.

## 🛠 Tech Used
Python, NumPy, Pandas, Matplotlib, Seaborn, Plotly

## 🚀 Business Impact
This analysis can support:
⚡ Smart home energy optimization systems
🏠 Utility companies in forecasting household energy demand
🌱 Energy efficiency initiatives and sustainability planning
📊 Data-driven decision-making for reducing electricity costs
By identifying key drivers of appliance energy consumption, this project demonstrates how predictive modeling can support energy efficiency and cost optimization strategies.
