
# Credit Card Fraud Detection

This project implements a Credit Card Fraud Detection system using a Logistic Regression model in Google Colab. The goal is to identify fraudulent transactions from a dataset of credit card transactions, leveraging machine learning techniques to enhance the accuracy of fraud detection.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Credit card fraud detection is essential for preventing financial losses and protecting consumers. This project utilizes a Logistic Regression model to classify transactions as either fraudulent or legitimate based on various features in the dataset.

## Installation

To run this project, open the provided Google Colab notebook.

1. **Open the Notebook:**

   You can open the notebook directly in Google Colab using the following link: [Credit Card Fraud Detection Notebook](https://colab.research.google.com/).

2. **Install Dependencies:**

   The notebook includes cells to install the necessary libraries. Run the cells that install libraries like `pandas`, `numpy`and `scikit-learn`.

## Usage

1. **Load the Dataset:**

   Upload the dataset (`credit_card_transactions.csv`) to the Colab environment. Modify the file path in the notebook if needed.
2. **Pre Process the dataset and Perform Data Analysis**
   this is a very important step as in this case, it showed that the dataset is highly unbalanced and that it needed an undersampling

3. **Train the Model:**

   Execute the cells in the notebook to preprocess the data, train the Logistic Regression model, and save the trained model.

4. **Evaluate the Model:**

   Run the evaluation cells to generate metrics such as accuracy, precision, recall, and F1-score.

5. **Make Predictions:**

   Use the cells provided to make predictions on new data by uploading `new_transactions.csv`.

## Dataset

The dataset used for this project is from the [Kaggle's Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It contains transactions made by credit cards in September 2013 by European cardholders.

## Results

The Logistic Regression model achieved the following performance metrics on the test set:

- **Accuracy:** 98.5%
- **Precision:** 97%
- **Recall:** 85%
- **F1-score:** 90%

These metrics demonstrate that the model performs well in detecting fraudulent transactions.

## Contributing

Feel free to contribute by submitting issues or improvements. Ensure that contributions align with the project's goals and adhere to best practices.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
