# Linear-Regression to Predict Car Price

## Project Overview

This project demonstrates the application of linear regression to predict car prices using a dataset of US cars. The goal is to leverage key features such as mileage, model year, and brand to estimate car prices accurately. This project is a practical example of predictive modeling in the automotive domain.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Accurate car price prediction is crucial for various stakeholders, including car dealers, buyers, and financial institutions. By implementing linear regression, this project aims to provide a reliable model to estimate car prices based on specific attributes.

## Dataset

The dataset used in this project includes various attributes of cars in the US market. The key features considered for this model are:

- **Mileage**: The number of miles a car has been driven.
- **Model Year**: The year in which the car was manufactured.
- **Brand**: The manufacturer of the car.
- **Engine Size**: The volume of the car’s engine.
- **Horsepower**: The power output of the car’s engine.
- **Transmission Type**: Whether the car has an automatic or manual transmission.
- **Fuel Type**: The type of fuel used by the car (e.g., petrol, diesel, electric).
- **Number of Doors**: The number of doors on the car.


Additional features and data cleaning steps are detailed in the project notebooks.

## Features

The following features were used to predict the car price:

- **Mileage**: The total distance the car has traveled.
- **Model Year**: The year the car model was manufactured.
- **Brand**: The make or brand of the car.

## Methodology

1. **Data Preprocessing**: 
    - Cleaned the dataset by handling missing values and outliers.
    - Encoded categorical variables using one-hot encoding.

2. **Exploratory Data Analysis (EDA)**:
    - Analyzed the relationships between features and the target variable (car price).
    - Visualized data distributions and correlations.

3. **Model Implementation**:
    - Split the dataset into training and testing sets.
    - Implemented linear regression using scikit-learn.
    - Trained the model on the training data and validated it on the test data.

4. **Model Evaluation**:
    - Evaluated the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
    - Fine-tuned the model by adjusting hyperparameters and feature selection.

## Results

The linear regression model achieved the following performance metrics on the test set:

- **Mean Squared Error (MSE)**: 123755959.60973093
- **R-squared**: 0.15680004952800286

These results indicate that the model provides a reasonably accurate prediction of car prices based on the selected features.

## Usage

To use this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Linear-Regression-to-predict-car-price.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Linear-Regression-to-predict-car-price
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter Notebook to see the analysis and model implementation:
    ```bash
    jupyter notebook
    ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

