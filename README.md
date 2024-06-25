# Real Estate Price Prediction Project

This repository contains the code and resources for predicting home prices in Bangalore using machine learning techniques.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Overview
The Bangalore Home Prices Prediction project aims to provide an accurate model for predicting the prices of homes in Bangalore based on various features such as location, size, total square feet, and more. The model is trained using regression techniques and evaluated for its performance.

## Dataset
The dataset used for training and testing the model contains information about various properties in Bangalore, including:
- Location
- Total square feet area
- Number of bedrooms
- Number of bathrooms
- Price

## Model
The model is built using Python with libraries such as Pandas, NumPy, Scikit-Learn, and Matplotlib. It employs linear regression to predict home prices based on the provided features.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ShrutiBhosale/Real_Estate_Price_Prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Real_Estate_Price_Prediction
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To predict home prices, you can use the `Real_Estate_Price_Prediction.ipynb` notebook or the provided scripts.

1. **Notebook:**
    - Open `Real_Estate_Price_Prediction.ipynb` in Jupyter Notebook or JupyterLab.
    - Follow the steps in the notebook to load the data, preprocess it, train the model, and make predictions.

2. **Script:**
    - Run the script to predict home prices based on user input:
    ```bash
    python predict_home_price.py --location "location" --sqft 1000 --bath 2 --bhk 3
    ```

## Results
The model's performance is evaluated using metrics such as Mean Absolute Error (MAE) and R-squared score. Below are the results obtained from the test dataset:

| Metric               | Value    |
| -------------------- | -------- |
| Mean Absolute Error  | XX.XX    |
| R-squared Score      | X.XX     |

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.

## Acknowledgements
- [codebasics](https://github.com/codebasics) for the original notebook and inspiration.
- Authors of the Python libraries used in this project.

---

*This project was developed with the help of the `Real_Estate_Price_Prediction.ipynb` notebook*
