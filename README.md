# Problem Understanding - Introduction


# 1. Data Pre-processing & Cleaning
## 1. Data Load & Cleaning [Page](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/1.1.Data_Load_And_Cleaning.ipynb)
- Load the dataset:
  - Save dataset on Colab (Zip & Single)
  - Check the dimension of the dataset
- Handle Missing Value:
  - Check Missing Value:
    - Identify missing values in each column
    - Dataframe to show the missing value with it's percentage
  - Strategy for Missing Value:
    1. Dropping rows or columns with missing values
    2. Imputation (filling missing values with a specific value, e.g., mean, median, mode)
      - Univariate:
        - Numerical: Mean, Median, Mode, End of the Distribution
        - Categorical: Mode, 'Missing'
      - Multivariate:
        - KNN Impute
        - Iterative Impute
    3. Using interpolation methods
    4. Forward and Backward Technique
    5. Depending on the context (Random Missing, Missing Indicator)

# 2. Exploratory Data Analysis (EDA)


# 3. Feature Engineering
## 3.1. Create New Features [Page](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.1.Create_New_Features.ipynb)
- Polynomial Features
- Interaction Features
- Binning or Discretization
- Remove Features with Correlation value:
  - Pearson Correlation
  - Point Biserial Correlation
  - Correlation Ratio
  - Cramer's V
