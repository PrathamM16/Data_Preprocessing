# Titanic Dataset Machine Learning Data PreProcessing Techniques

This project preprocesses the Titanic dataset for machine learning models using scikit-learn.

## Installation

```bash
pip install pandas scikit-learn


Clone: git clone https://github.com/yourusername/your-repository.git
Navigate to the directory: cd your-repository
Run the script: python your_script.py

Data

The dataset used (Titanic-Dataset.csv) contains information about passengers on the Titanic, such as age, fare, class, sex, and embarked port.
Code Explanation

    Loads the dataset (Titanic-Dataset.csv) and separates features (X) and target variable (y).
    Preprocesses numerical data by imputing missing values using the median and scaling using StandardScaler.
    Preprocesses categorical data by imputing missing values with the most frequent value and performing one-hot encoding using OneHotEncoder.
    Combines numerical and categorical preprocessing into a ColumnTransformer.
    Splits the preprocessed data into training and testing sets using train_test_split.

