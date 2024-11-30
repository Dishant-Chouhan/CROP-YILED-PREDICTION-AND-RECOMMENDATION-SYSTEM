# Crop Recommendation and Yield Prediction

## Overview
The **Crop Recommendation and Yield Prediction System** is a machine learning-based application designed to assist farmers in making informed decisions about crop cultivation and yield forecasting. By analyzing input features like soil properties, climate conditions, and agronomic practices, the system provides accurate crop recommendations and yield predictions, helping farmers optimize productivity and sustainability.

---

## Features
- **Crop Recommendation**: Suggests the most suitable crops for cultivation based on factors like soil type, NPK levels, and climate conditions using the Gradient Boosting algorithm.
- **Yield Prediction**: Forecasts crop yields based on weather parameters, soil characteristics, and farming practices using the Random Forest algorithm.
- **Interactive Web Interface**: A user-friendly platform built with Flask to input data and view recommendations and predictions.
- **Actionable Insights**: Empowers farmers with reliable data to improve decision-making and optimize resource allocation.

---

## Technologies Used

### Programming Tools and Libraries
- **Python**: Core programming language for developing the algorithms and application.
- **Flask**: Framework for building the web application interface.
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For implementing machine learning algorithms (Gradient Boosting and Random Forest).
- **Matplotlib/Seaborn**: For data visualization during analysis.

### Machine Learning Algorithms
1. **Crop Recommendation**: Gradient Boosting  
   - Uses decision trees built iteratively to minimize prediction errors.
   - Analyzes factors like soil nutrients (NPK), temperature, humidity, and precipitation to recommend the most suitable crops.
2. **Yield Prediction**: Random Forest  
   - Combines multiple decision trees to predict crop yields based on features like soil type, weather conditions, and agronomic practices.
   - Handles complex datasets and provides robust predictions.

---

