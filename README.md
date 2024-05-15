Data Science Workflow Notebook: [Click Here](https://docs.google.com/document/d/1yxul-IzD_0L_jeFiIUAPm0ksZVJfQyrF_scu3YIFCh0/edit?usp=sharing)

# 1. Data Pre-processing & Cleaning
## 1.1. Data Load & Cleaning [Click Here](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/1.1.Data_Load_And_Cleaning.ipynb)
1. Load the dataset:
    - Save dataset on Colab (Zip & Single)
    - Check the dimension of the dataset
2. Handle Missing Value:
    - Check Missing Value:
      - Identify missing values in each column
      - Dataframe to show the missing value with it's percentage
    - Strategy for Missing Value:
      1. Dropping rows or columns with missing values
      2. Imputation (filling missing values with a specific value, e.g., mean, median, mode)
          - Univariate :
            - Numerical : Mean, Median, Mode, End of the Distribution
            - Categorical : Mode, 'Missing'
          - Multivariate :
            - KNN Impute
            - Iterative Impute
      3. Using interpolation methods
      4. Forward and Backward Technique
      5. Depending on the context (Random Missing, Missing Indicator)
3. Handle Duplicates
    - Identify Duplicates
    - Drop Duplicates
     

# 2. Exploratory Data Analysis (EDA)
## 2.1. EDA_Target_Correlation [Click Here](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/2.1.EDA_Target_Correlation.ipynb)
1. Explore Distribution of Target Variable
    - Visualize the distribution of the target variable
    - Visualize the target variable skewness and histogram
    - Transformation to achieve a symmetrical distribution
2. Visualize the Relationship between features and Target
    - 2.2. Visualization Page
3. Explore Correlations between Features
    - Compute pairwise correlation
    - Visualize Correlation using Heatmap (regression)
    - Identify Highly Correlated Columns :
      - Regression
      - Classification :
           - Binary Classification (Point Biserial)
           - Categorical Classification (Correlation Ratio)
           - Categorical Classification (Cramer's V)
   - Drop Highly Correlated Columns
          

# 3. Feature Engineering
## 3.1. Create New Features [Click Here](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.1.Create_New_Features.ipynb)
1. Create New Features:
    - Polynomial Features
    - Interaction Features
    - Binning or Discretization
2. Remove Features with Correlation value:
      - Pearson Correlation
      - Point Biserial Correlation
      - Correlation Ratio
      - Cramer's V
  
## 3.2. Transform Skewed Columns [Click Here](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.2.Transform_Skewed_Columns.ipynb)
1. Identify Skewed Columns
    - Visualization of the Skewed Columns
2. Handle Skewed Columns
    - Find the lowest skewed columns.
    - Transform Skewed Columns
  
## 3.3. Feature Selection [Click Here](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.3.Feature_Selection.ipynb)
1. Identify Important columns :
   a. Variance Threshold
   b. Select Features using Mutual Info Classification
   c. Select Features using Mutual Info Regression
   d. Select Feature using Chi2 Statistical Analysis
   e. Ranked Best feature using Univariate Analysis
   f. Ranked Best Features using ANOVA
   g. Select Features using ExtraTreesClassifier
   i. Recursive Feature Elimination (RFE)
