# Hourly-Bike-Sharing-Demand-Prediction-Using-Machine-Learning
### **Introduction**  

Bike-sharing systems have become an essential component of urban mobility, providing an eco-friendly and cost-effective alternative for daily commuting. Accurately predicting the demand for bike rentals at different hours of the day is crucial for efficient fleet management, ensuring availability at high-demand locations, and optimizing resource allocation. This project focuses on forecasting the number of bike rentals per hour using machine learning techniques based on various influencing factors such as weather conditions, time of day, seasonality, humidity, wind speed, and day type (weekday or weekend).  

The dataset used in this study, `hour.csv`, contains historical bike-sharing data with multiple features that influence demand. The goal is to leverage data preprocessing techniques such as feature scaling, encoding categorical variables, and applying regression models to develop a predictive system. By analyzing patterns and relationships in the data, we aim to build a robust model that can assist in real-time decision-making for bike-sharing service providers.  

Machine learning models, including linear regression and advanced predictive techniques, will be evaluated based on metrics such as Mean Squared Error (MSE) and R-squared (R²) to determine their effectiveness. The insights from this analysis can help improve urban transportation planning, reduce congestion, and enhance user experience in bike-sharing services.
Objective:
Predict the number of bike-sharing rentals per hour using different environmental and temporal factors.

**Key Steps:**
**Loading Required Libraries:**
1) pandas, numpy (Data manipulation)
2) sklearn (Machine learning: Linear Regression, Scaling, Encoding, Model Evaluation)
3) matplotlib.pyplot & seaborn (Visualization)

**Reading the Dataset:**
1) Loads hour.csv containing bike-sharing data.
2) Displays the first few rows (df.head()).
3) Checks the data types of columns (df.dtypes).
