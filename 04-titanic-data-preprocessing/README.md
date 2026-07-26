# Titanic Data Preprocessing

Practicing data preprocessing steps on the Titanic dataset, preparing raw data to be model ready. Covers handling missing values, encoding categorical data, scaling features, and splitting data into training and testing sets.

## What is covered
- Handling missing values (median imputation for age, filling deck and embark_town with an "Unknown" category, dropping rows with missing embarked)
- Dropping repeated/duplicate columns (class, alive, who, embarked)
- Encoding categorical columns using One-Hot Encoding (pd.get_dummies) for sex, embark_town, and deck
- Handling Categorical dtype columns using cat.add_categories before filling missing values
- Feature scaling using StandardScaler
- Train/Test split using sklearn (80/20)

## Concepts practiced
- Difference between fillna and dropna approaches
- Why missing data itself can be meaningful (deck's "Unknown" category)
- Handling pandas Categorical dtype restrictions
- Why raw data breaks models (missing values, text categories, different scales)

## Dataset
Titanic dataset from seaborn (`sns.load_dataset('titanic')`)
