
---

# Bank Customer Churn Prediction

Welcome to the Bank Customer Churn Predictor project! This project leverages machine learning to predict customer churn in banking institutions. Customer churn refers to customers who stop doing business with a company, and predicting it helps banks improve customer retention and business sustainability.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Notebook](#notebook)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

Customer churn prediction is crucial for the banking sector as it helps in identifying customers who are likely to leave and take preventive actions. This project uses a machine learning model to predict churn based on various customer attributes.

## Features

- **Data Preprocessing:** Cleans and prepares the dataset for modeling.
- **Machine Learning Model:** Uses a classifier (e.g., Random Forest, XGBoost, Logistic Regression, Decision Tree, KNeighbors, Gradient Boosting, support vector classifier)     to predict customer churn.
- **Jupyter Notebook:** An interactive notebook for training the model and making predictions.

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/siddarammanur656/bank customer churn predictor model.git
cd bank customer churn predictor model
pip install -r requirements.txt
```

## Usage

### Running the Jupyter Notebook

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Open the Notebook:**
   In the Jupyter interface, open the `customer churn prediction model.ipynb` notebook.

3. **Run the Notebook:**
   Execute the cells in the notebook to preprocess data, train the model, and make predictions.

## Dataset

The dataset used in this project consists of various customer attributes, such as:

- Customer ID
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure with the bank
- Balance
- Number of Products
- Whether they have a credit card
- Whether they are active members
- Estimated Salary
- Exited

Please ensure that the dataset is placed in the `data` directory.

## Model

The project uses a machine learning classifier to predict churn. The model is trained on historical customer data and validated to ensure accuracy.

### Model Training

The notebook handles data preprocessing, feature selection, and training the classifier.

### Model Prediction

The notebook also includes cells to input new customer data and predict the likelihood of churn.

## Notebook

The Jupyter Notebook (`customer churn prediction model.ipynb`) provides an interactive way to:

- Load and preprocess data
- Train the machine learning model
- Evaluate model performance
- Make predictions on new data

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact us at [info@bankchurnpredictor.com](mailto:siddarammanur656@gmail.com).

---
