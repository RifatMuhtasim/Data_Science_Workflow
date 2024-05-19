Data Science Workflow Notebook: [Click Here](https://docs.google.com/document/d/1yxul-IzD_0L_jeFiIUAPm0ksZVJfQyrF_scu3YIFCh0/edit?usp=sharing)

# 1. Data Pre-processing & Cleaning
## 1.1. Data Load & Cleaning [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/1.1.Data_Load_And_Cleaning.ipynb) | [Colab](https://drive.google.com/file/d/19l6YqD5Rg5Ow8cOL87svnrUzuKb8WEyM/view?usp=sharing)
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
## 2.1. EDA_Target_Correlation [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/2.1.EDA_Target_Correlation.ipynb) | [Colab](https://drive.google.com/file/d/1Mh7Ht-2Nz_dtN_G6NNS1xgkjhHjqvxLJ/view?usp=sharing)
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
## 3.1. Create New Features [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.1.Create_New_Features.ipynb) | [Colab](https://drive.google.com/file/d/1k6-XEIR7KYoDXzFJNGMM5-Pe-2uS-OHZ/view?usp=sharing)
1. Create New Features:
    - Polynomial Features
    - Interaction Features
    - Binning or Discretization
2. Remove Features with Correlation value:
      - Pearson Correlation
      - Point Biserial Correlation
      - Correlation Ratio
      - Cramer's V
  
## 3.2. Transform Skewed Columns [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.2.Transform_Skewed_Columns.ipynb) | [Colab](https://drive.google.com/file/d/1TGHJb0sA4W8GLJnXi6nnBcVI0CzCGcLy/view?usp=sharing)
1. Identify Skewed Columns
    - Visualization of the Skewed Columns
2. Handle Skewed Columns
    - Find the lowest skewed columns.
    - Transform Skewed Columns

  
## 3.3. Feature Selection [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.3.Feature_Selection.ipynb) | [Colab](https://drive.google.com/file/d/1rretglhQt2YNy2XJEO0hU6cWxNuTRlDM/view?usp=sharing)
1. Identify Important columns : <br/>
    a. Variance Threshold <br/>
    b. Select Features using Mutual Info Classification <br/>
    c. Select Features using Mutual Info Regression <br/>
    d. Select Feature using Chi2 Statistical Analysis <br/>
    e. Ranked Best feature using Univariate Analysis <br/>
    f. Ranked Best Features using ANOVA <br/>
    g. Select Features using ExtraTreesClassifier <br/>
    i. Recursive Feature Elimination (RFE) <br/>
2. Remove Unnecessary Features


## 3.4. Handle Outliers [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.4.Handle_Outliers.ipynb) | [Colab](https://drive.google.com/file/d/1ZGerL_F5gERFzfl-lEyZMwzk5jMLBqDo/view?usp=sharing)
1. Identify Outliers
2. Remove Outliers
    - IQR
    - STD
    - Percentile
3. Capping or Winsorization


## 3.5. Encode and Scaled Features [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/3.5.Encode_and_Scaled_Features.ipynb) | [Colab](https://drive.google.com/file/d/1Gx9F9J3Zxf5FOPH_-nPLJLKGt1qQYtZO/view?usp=sharing)
1. Encode categorical variables
    - One Hot Encoding
    - Label Encoding
    - Ordinal Encoding
2. Handling Class Imbalance (for Classification)
    - SMOTE
    - Undersampling
    - Oversampling
3. Scaled Numerical Features
    - Standardization
    - Normalization - MinMaxScaler
    - Robust Scaler



# 4. Model Selection
## 4.1. Model Selection [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/4.1.Model_Selection.ipynb) | [Colab](https://drive.google.com/file/d/1JuCjcKY2RADr6iH_qKSWLFdBPoxCyl-i/view?usp=sharing)
1. Split the Dataset 
    - Train Test Split
    - Time Series Split
2. Choose Baseline Models
    - Linear Regression
    - Logistic Regression
  

## 4.2. Regression Model [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/4.2.Regression_Model.ipynb) | [Colab](https://drive.google.com/file/d/1bvVlnaqoiEpkqLTBRlgj6VTIZh64zQcj/view?usp=sharing)
1. Machine Learning Model
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
    - SVM Regressor
    - K-Nearest Neighbors Regressor
    - XGB Regressor
2. Neural Network
    - Deep Learning (ANN for Regression)
3. Hyperparameter Tuning (GridSearchCV)
4. Hyperparameter Tuning for Neural Network
    - Using Deep Learning Hyperparameters params
  

## 4.3. Classification Model [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/4.3.Classification_Model.ipynb) | [Colab](https://drive.google.com/file/d/1cSh2ExeMUEA9uaDcDhwfbcaVuZDCJz5B/view?usp=sharing)
1. Machine Learning Model
    - Logistic Regression
    - Decision Tree
    - Random Forest
    - Support Vector Machine (SVM)
    - K-Nearest Neighbors (KNN)
    - Naive Bayes
    - XGBoost
2. Neural Network (Deep Learning)
3. Hyperparameter Tuning (GridSearchCV)
4. Hyperparameter Tuning for Neural Network
    - Using Parameters on Neural Network
5. Intrepert the model Result
6. Final Model Training


## 4.4. Unsupervised Model [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/4.4.Unsupervised_Model.ipynb) | [Colab](https://drive.google.com/file/d/1H-718q2HQDzS4oBx141cwHGg75vt47dg/view?usp=sharing)
1. KMeans Clustering
2. Hierarichal Clustering
3. DBSCAN


## 4.5. Time Series Forecast Model [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/4.5.Time_Series_Forecast_Model.ipynb) [Colab](https://drive.google.com/file/d/1xTOM9OjtJPE6ooOd-NBybA2GJXZ0N89o/view?usp=sharing)
1. ARIMA
    - Find p,d,q value
    - Model & Forecast
2. SARIMAX
3. FBProphet
4. LSTM Univariate
    - Prepare Data
    - Building LSTM Model
    - Predictions
5. LSTM Multivariate


#  5. Model Training and Evaluation 
## 5.1. Optuna Regression Hyperparameter [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/5.1.Optuna_Regression_Hyperparameter.ipynb) | [Colab](https://drive.google.com/file/d/18Z79SfZP5pdLn6Oq_FNFy2iYP8NKfmrG/view?usp=sharing)
1. Optuna
    - Linear Regression
    - XGBRegressor
    - Decision Tree Regressor
    - Random Forest Regressor
    - Support Vector Regressor
    - KNeighbors Regressor
2. Mutliple Optuna Model


## 5.2. Optuna Classification Hyperparameter [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/5.2.Optuna_Classification_Hyperparameter.ipynb) | [Colab](https://drive.google.com/file/d/10E4wc10DIR02HuzK8ztnqnSTWffNmplm/view?usp=sharing)
1. Optuna
    - Logistic Regression
    - XGBoost
    - Random Forest
    - Decision Tree Classifier
    - Support Vector Machine
    - KNeighbors Classifier
    - Gaussian NB
    - Multinomial NB
2. Multiple Optuna Model
3. Model Using Stratified K-Fold
    - Logistic Regression
    - XGBoost Stratified
    - KNeighbors Classifier


# 6. Ensemble Methods
## 6.1. Ensemble Methods [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/6.1.Ensemble_Methods.ipynb) | [Colab](https://drive.google.com/file/d/1N7UpMdtdRxQOF0_J7OdNATgeIqdNTtkE/view?usp=sharing)
1. Voting
2. Stacking
3. Bagging
4. Boosting
5. Boosting ML Algo
    - Light GBM
    - Cat Boost
    - Hyperparameter Tuning
  

## 6.2. Model Evaluation [Github](https://github.com/RifatMuhtasim/Data_Science_Workflow/blob/main/6.2.Model_Evaluation.ipynb) | [Colab](https://drive.google.com/file/d/1UP43vtA1YjmW49ctsY-A81CyrXMy1i5U/view?usp=sharing)
1. Evaluation of the validation set
2. Final Model Training
3. Evaluate on the Test Data
