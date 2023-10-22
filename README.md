

```markdown
# Fake News Classifier 

This repository contains code for a text classification project using Python and the scikit-learn library. The project involves reading a dataset from a CSV file, preprocessing the text data, and building a machine learning model to classify the text into different categories.

## Dataset
The dataset used in this project is stored in the 'train.csv' file. It is a labeled dataset where each text entry is associated with a 'label' that represents its category.

## Dependencies
- pandas
- scikit-learn
- nltk
- re

You can install these dependencies using `pip`:
```
pip install pandas scikit-learn nltk
```

## Code Overview
- `read_csv` - Reads the dataset from 'train.csv' using the pandas library.
- Data Preprocessing:
  - Extracts independent (X) and dependent (Y) features.
  - Performs data cleaning, removing any rows with missing values.
  - Tokenizes, lowers case, and stems the text data using the NLTK library.
- Feature Extraction:
  - Uses the CountVectorizer from scikit-learn to convert the text data into a numerical format.
- Train-Test Split:
  - Splits the dataset into training and testing sets using `train_test_split` from scikit-learn.
- `get_feature_names_out` - Gets feature names from the CountVectorizer.
- `get_params` - Gets parameters used in the CountVectorizer.
- `count_df` - Creates a DataFrame of the training data with feature names.





## Acknowledgments
- [Pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [NLTK](https://www.nltk.org/)


