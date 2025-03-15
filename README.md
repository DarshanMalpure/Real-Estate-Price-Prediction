# Real Estate Price Prediction – Data Science Regression Project

This data science project walks through a step-by-step process of how to build a **real estate price prediction website**.

## Project Overview

1. **Model Building**
   - We will use **scikit-learn** and **Linear Regression** to build a model using the **Bangalore home prices dataset** from [Kaggle](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data).
   
2. **Flask Server**
   - Next, we'll write a **Python Flask server** that loads the trained model and serves HTTP requests to predict home prices.

3. **Web Application**
   - Finally, we will build a **website using HTML, CSS, and JavaScript** that allows users to enter inputs like home square footage, number of bedrooms, etc.
   - The website will send these inputs to the Flask server and display the predicted price to the user.

## Data Science Concepts Covered

- Data loading and cleaning  
- Outlier detection and removal  
- Feature engineering  
- Dimensionality reduction  
- Hyperparameter tuning using `GridSearchCV`  
- Model validation using **K-Fold Cross Validation**

## Technologies and Tools Used

- **Python**
- **Numpy** and **Pandas** – for data manipulation and cleaning
- **Matplotlib** – for data visualization
- **Scikit-learn** – for building and evaluating ML models
- **Jupyter Notebook**, **Visual Studio Code**, **PyCharm** – IDEs for development
- **Flask** – to create a lightweight HTTP server in Python
- **HTML / CSS / JavaScript** – to build a user-friendly front-end interface
