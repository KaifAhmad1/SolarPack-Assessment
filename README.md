# Solar Energy Forecasting and Solar Panel Angle Optimization 
This repository contains a comprehensive solution to two distinct problems related to solar energy utilization:

## **Solar Energy Production Forecasting Model**
- **Problem Statement:**
Design and develop a machine learning model capable of forecasting solar energy production.

- **Objective:**
The objective of this problem statement is to develop a machine learning model capable of accurately forecasting energy production based on environmental factors such as ambient temperature, humidity, and wind speed.

- **Solution:** 
The solution provides a machine learning model for forecasting energy production. It involves data loading, exploration, preprocessing, and building various models including Decision Tree, Random Forest, Gradient Boosting, and LSTM. The models are trained, evaluated, and compared to identify the most effective approach for accurate energy production forecasting.

- ###  **Key Components:**
  
#### **Installation and Imports**
- Ensure necessary packages like `pvlib` installed along with their dependencies.

#### **Data Loading and Exploration**
- Load data from a CSV file into a Pandas DataFrame. Perform initial exploration including checking data information, identifying null values, and converting date and time columns into datetime format.

#### **Data Preprocessing**
- Set date and time columns as the index and drop redundant columns.

#### **Exploratory Data Analysis (EDA)**
- Perform statistical summaries, correlation analysis, and visualizations like pairplots and correlation heatmaps to gain insights into the data.

#### **Time Series Analysis**
- Generate time series plots for power output, humidity, and wind speed. Explore seasonal variations and trends in ambient temperature and humidity using box plots and histograms.

#### **Model Building and Training**
- Build and train various machine learning models including Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, and Deep Neural Network LSTM Model.

#### **Model Loss over Epochs**
- Visualize training and validation loss over epochs for the LSTM model.

#### **Saving and Loading the Model**
- Save the trained LSTM model to a file and load it back for further evaluation or deployment.

#### **Evaluation of Loaded LSTM Model**
- Evaluate the loaded LSTM model by making predictions on the test data and calculating metrics like mean squared error and mean absolute error.

#### **Model Comparison**
- Compare the mean squared error of different models (Decision Tree, Random Forest, Gradient Boosting, LSTM) using a line plot for better understanding and selection.

#### **Dataset Used**
[Horizontal photovoltaic power output data for 12 sites in the Northern Hemisphere](https://www.kaggle.com/datasets/saurabhshahane/northern-hemisphere-horizontal-photovoltaic)

#### **Notebook Link:** 
- Please find the Google Colab link provided below for an in-depth exploration of our data analysis and corresponding graphs. To enhance your understanding, we've utilized Plotly for visualization, offering dynamic charts and plots.It's worth noting that these dynamic visualizations are not saved on GitHub, so the Colab environment is essential for accessing them effectively.
- [Energy Forecasting Model](https://colab.research.google.com/drive/1zy4bHSD3aVoKNw62OoPv7KWO8cQDxxS-?usp=sharing)



## **Optimal Solar Panel Angle Optimization Model**
- **Problem Statement:**
The efficiency of solar panels is highly dependent on their orientation concerning the sun. Finding the optimal angles for solar panel placement can significantly enhance energy capture and utilization.

- **Objective:**
The notebook aims to optimize solar panel performance using machine learning by integrating and preprocessing solar-related datasets, analyzing solar position and irradiance, exploring environmental factors, and implementing predictive models to predict key performance metrics. Through this analysis, it seeks to provide actionable insights for enhancing solar energy efficiency and sustainability.

- **Solution:**
The objective of this notebook is to provide a comprehensive analysis and optimization framework for solar panel performance using machine learning and deep learning techniques. The notebook aims to achieve the following goals:

- ###  **Key Components:**

 ####  **Data Loading and Preprocessing:** 
  - Import necessary libraries and load datasets related to `solar angles`, `solar forecasting`, and `historical weather data`.
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
- Model performance metrics including `MSE`, `R2 scores`, and feature importance rankings.

#### **Dependencies:**

- Libraries such as pandas, numpy, pvlib, sklearn, plotly, tensorflow, keras for data manipulation and solar-related calculations.

#### **Insights:** 

- Over 20,000 entries in the merged dataset, providing significant data for analysis and model training.
- Comprehensive consideration of various parameters such as solar angles, environmental factors, and total irradiance for optimizing solar panel performance.

#### **Notebook Link:** 
- Please find the Google Colab link provided below for an in-depth exploration of our data analysis and corresponding graphs. To enhance your understanding, we've utilized Plotly for visualization, offering dynamic charts and plots.It's worth noting that these dynamic visualizations are not saved on GitHub, so the Colab environment is essential for accessing them effectively.
- [National Solar Radiation Database(NSRDB) Solar Radiation and Meteorological Dataset](https://www.kaggle.com/datasets/ibrahimkiziloklu/solar-radiation-dataset)


#### **Datasets Used:** 
[National Solar Radiation Database(NSRDB) Solar Radiation and Meteorological Dataset](https://www.kaggle.com/datasets/ibrahimkiziloklu/solar-radiation-dataset)


License
This project is licensed under the MIT License - see the LICENSE file for details.

Author
Mohd Kaif


References 
