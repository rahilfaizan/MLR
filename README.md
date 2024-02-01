# MLR (Multiple Linear Regression) from Scratch

This repository contains Python code for implementing Multiple Linear Regression (MLR) from scratch. The MLR model is trained and evaluated on a dataset related to Lego prices. The code utilizes basic mathematical operations and linear algebra concepts to implement MLR without relying on external libraries for the core regression functionality.

## Requirements

- Python 3.x
- NumPy
- pandas
- matplotlib
- scikit-learn (for comparison)

Install the required dependencies using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/rahilfaizan/MLR.git
```
## Dataset

The MLR model is trained on the Lego dataset loaded from the "lego.csv" file. The dataset includes various features such as Pieces, Price, Pages, Unique Pieces, and Amazon Price. Some preprocessing steps are performed, including handling missing values and dropping unnecessary columns.

## Implementation Details

The MLR is implemented step by step, starting with data loading and preprocessing, followed by correlation analysis and scatter plots. The core MLR model is then built using matrix operations, and predictions are compared to scikit-learn's Linear Regression model.

## Results

The results include scatter plots illustrating the relationship between input features (Pieces, Price, Pages, Unique Pieces) and the target variable (Amazon Price). Additionally, mean absolute error (MAE) and mean squared error (MSE) are calculated to evaluate the performance of the implemented MLR model compared to scikit-learn's Linear Regression.
