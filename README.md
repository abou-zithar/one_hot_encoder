# Data Preprocessing and Linear Regression Example

This is a simple example showcasing data preprocessing and linear regression using Python's pandas and scikit-learn libraries. The example involves predicting house prices based on town and area features.

## Prerequisites

- Python (3.7+ recommended)
- pandas
- scikit-learn

## Getting Started

1. Clone this repository or copy the code snippets into your project folder.
2. Make sure you have the required libraries installed using:
```python
pip install pandas scikit-learn

```
3. Place your dataset `homeprices.csv` in the same directory as the script.

## Code Explanation

The code is divided into different sections, each performing a specific task:

### Data Loading and Feature Encoding

- The dataset is loaded using pandas' `read_csv()` function.
- One-hot encoding is used to convert categorical feature "town" into binary columns. This is achieved using both pandas' `get_dummies()` function and scikit-learn's `OneHotEncoder`.

### Data Splitting

- The dataset is split into features (X) and the target variable (y).

### Linear Regression

- A linear regression model is created using scikit-learn's `LinearRegression()` class.
- The model is trained using the features and target variable.
- Model predictions are made for a sample input.

## Usage

1. Update `homeprices.csv` with your own dataset if needed.
2. Run the script and observe the output.

## Note

- The provided dataset and code snippets are for educational purposes and might require modifications to work with other datasets.
- The accuracy score (`model.score()`) and predictions might vary depending on the dataset and model complexity.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

