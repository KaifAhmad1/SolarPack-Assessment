# Solar Energy Forecasting and Solar Panel Angle Optimization 
This repository contains a comprehensive solution to two distinct problems related to solar energy utilization:

## **Solar Energy Production Forecasting Model**
- **Problem Statement:**
The efficiency of solar panels is highly dependent on their orientation concerning the sun. Finding the optimal angles for solar panel placement can significantly enhance energy capture and utilization.

- **Objective:**
The notebook aims to optimize solar panel performance using machine learning by integrating and preprocessing solar-related datasets, analyzing solar position and irradiance, exploring environmental factors, and implementing predictive models to predict key performance metrics. Through this analysis, it seeks to provide actionable insights for enhancing solar energy efficiency and sustainability.

- **Solution:** 


## **Optimal Solar Panel Angle Optimization Model**
- **Problem Statement:**
The efficiency of solar panels is highly dependent on their orientation concerning the sun. Finding the optimal angles for solar panel placement can significantly enhance energy capture and utilization.

- **Objective:**
The notebook aims to optimize solar panel performance using machine learning by integrating and preprocessing solar-related datasets, analyzing solar position and irradiance, exploring environmental factors, and implementing predictive models to predict key performance metrics. Through this analysis, it seeks to provide actionable insights for enhancing solar energy efficiency and sustainability.

- **Solution:**
The objective of this notebook is to provide a comprehensive analysis and optimization framework for solar panel performance using machine learning and deep learning techniques. The notebook aims to achieve the following goals:

- ###  **Key Components:**

 ####  **Data Loading and Preprocessing:** 
  - Import necessary libraries and load datasets related to solar angles, solar forecasting, and historical weather data.
  - Combine data from different sources for comprehensive analysis.
  - Explore and preprocess loaded datasets including handling missing values and converting columns to appropriate data types.
  
#### **Solar Position Analysis:**

- Calculate various solar position parameters such as zenith angle, azimuth, and elevation.
- Analyze the distribution and temporal patterns of solar position variables.
- Gain insights into seasonal patterns and atmospheric effects on solar position.
  
#### **Total Irradiance Calculation and Analysis:**

- Calculate total irradiance components like POA global, direct, diffuse, sky diffuse, and ground diffuse.
- Analyze seasonal variations and their impact on solar panel efficiency.
  
#### **Environmental Factor Analysis:**

- Analyze environmental factors such as humidity, temperature, wind speed, and surface albedo.
- Understand the typical ranges and distributions of environmental factors.
  
#### **Feature Importance and Model Implementation:**

- Perform feature importance analysis and model implementation using Random Forest Regressor and Gradient Boosting Regressor.
- Train models for target variables including POA Global Irradiance, Surface Tilt, and Surface Azimuth.
- Evaluate model performance using mean squared error (MSE) and R-squared (R2) scores.
  
#### **Deep Neural Network (LSTM) Model:**

- Implement a Long Short-Term Memory (LSTM) neural network for predictive modeling.
- Preprocess data, define the model architecture, and compile it with appropriate loss functions and optimizers.
- Monitor training and validation losses and mean absolute error (MAE).

#### **Output:**
- Merged dataset containing solar angles, weather conditions, and geographical location.
- Model performance metrics including MSE, R2 scores, and feature importance rankings.

#### **Dependencies:**

- Libraries such as pandas, numpy, and pvlib for data manipulation and solar-related calculations.

#### **Insights:** 

- Over 20,000 entries in the merged dataset, providing significant data for analysis and model training.
- Comprehensive consideration of various parameters such as solar angles, environmental factors, and total irradiance for optimizing solar panel performance.

Repository Structure
/panel_angle_algorithm: Contains the implementation of the solar panel angle optimization algorithm.
README.md: Main readme file detailing project overview, setup instructions, and usage guidelines.
Usage
Users can interact with the algorithm to compute optimal solar panel angles for any given location and date. Detailed instructions on how to use the algorithm and interpret the results are available in the documentation.

Setup Instructions
To set up the project locally, follow the setup instructions provided in the respective directories (short_term_model, long_term_model, panel_angle_algorithm).

Contributing
Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Authors
Your Name
Acknowledgments
We would like to thank the following individuals and organizations for their contributions and support:

[List any acknowledgments here]
References
[List any external data sources or references used in the project]
