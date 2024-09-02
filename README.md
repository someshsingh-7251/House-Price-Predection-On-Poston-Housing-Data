# House Price Prediction on Boston Housing Data
## Overview
This project leverages machine learning to predict house prices based on the Boston Housing dataset. The dataset includes various features that influence housing prices, such as crime rate, the proportion of non-retail business acres, the number of rooms, and more. The goal of this project is to build and evaluate models that can accurately predict housing prices.

## Features
- **Data Preprocessing:** Includes data cleaning, handling missing values, feature scaling, and data transformation.
- **Exploratory Data Analysis (EDA):** Visualization and analysis of features to understand their impact on house prices.
- **Model Building:** Implementation of various regression models such as Linear Regression, Ridge Regression, Lasso Regression, and Random Forest Regressor.
- **Model Evaluation:** Assessing model performance using metrics like Mean Squared Error (MSE), R-squared, and cross-validation.

## Dataset
The dataset used in this project is the famous Boston Housing dataset, which contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts. It includes 506 instances with 13 attributes (features).

- **CRIM:** Per capita crime rate by town.
- **ZN:** Proportion of residential land zoned for lots over 25,000 sq. ft.
- **INDUS:** Proportion of non-retail business acres per town.
- **CHAS:** Charles River dummy variable (1 if tract bounds river; 0 otherwise).
- **NOX:** Nitric oxides concentration (parts per 10 million).
- **RM:** Average number of rooms per dwelling.
- **AGE:** Proportion of owner-occupied units built prior to 1940.
- **DIS:** Weighted distances to five Boston employment centers.
- **RAD:** Index of accessibility to radial highways.
- **TAX:** Full-value property tax rate per $10,000.
- **PTRATIO:** Pupil-teacher ratio by town.
- **B:** Proportion of African Americans by town.
- **LSTAT:** Percentage of lower status of the population.
- **MEDV:** Median value of owner-occupied homes in $1000s (Target Variable).

## Installation
To run this project locally, follow these steps:

**1. Clone the repository:**

    git clone https://github.com/someshsingh-7251/house-price-prediction.git
**2. Navigate to the project directory:**

    cd house-price-prediction
**3. Create a virtual environment:**

    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
**4. Install the dependencies:**

    pip install -r requirements.txt
**5. Run the Jupyter Notebook:**

    jupyter notebook

## Usage
- **Data Preprocessing:** The data_preprocessing.py script includes functions for cleaning and transforming the data.
- **Exploratory Data Analysis:** Use the EDA.ipynb notebook to explore the data, visualize relationships between features, and gain insights.
- **Model Training and Evaluation:** The model_training.py script is where models are built, trained, and evaluated. Results are stored in the results/ directory.

## Results
The performance of different models is compared based on their accuracy and error metrics. The project provides insights into which features most significantly impact house prices in the Boston area.

## Contributing
Contributions are welcome! Please submit a pull request or create an issue to discuss any improvements or changes.

## License
This project is licensed under the MIT License. See the *LICENSE* file for more details.

## Note:
Feel Free to Contact at Instagram: https://www.instagram.com/officialsomeshchinkusingh?igsh=MW1vdTZwbDdmMTZxbw==
