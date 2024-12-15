# Predicting Joint Shear Strength of Reinforced-Fiber Concrete(FRC)

Develop machine learning-based models to predict the joint shear strength of FRC beam-to-column connections across various fiber types.
Algorithms used are listed as the following:
- Linear Regression
- Support Vector Regression
- Random Forest

Each algorithm listed above explored 2 different approaches:
- Mechanically consistent: Using a provided equations from previous research (Linear Regression and SVR share the same equation)
- Mechanically inconsistent: Using all input parameters in the dataset that's known to be influential when computing joint shear strength

Here's the repository structure:

```
ML_FALL2024/
├── data_analysis/
│   ├── linear_regression.ipynb       
│   ├── random_forest_case1.ipynb       
│   ├── random_forest_case2.ipynb       
│   ├── SVR_2approaches.ipynb       
├── requirements.txt                    # Dependencies for the notebook
├── input_data                          # Contain the dataset
├── linear_regression_results/          # Picture of linear regression results
├── random_forest_results/              # Picture of random forest results                             
├── svr_results/                        # Picture of SVR results
├── README.md                          # Project documentation
```
## Setup Instructions

### Step 1: Unzip the file to your local machine

### Step 2: Install dependencies
`pip install -r requirements.txt`

### Step 3: Run the notebook
1. Open the desired model
2. Execute shell by Shift+Enter or click run all
