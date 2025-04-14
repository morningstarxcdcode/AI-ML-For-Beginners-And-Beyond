# Data Preprocessing Cheat Sheet

## 1. **Handling Missing Data**
- **Methods**: 
  - Remove missing data.
  - Impute using mean, median, or mode.
  - Use machine learning models to predict missing values.

## 2. **Feature Scaling**
- **Methods**: 
  - **Standardization**: Transform data to have a mean of 0 and a standard deviation of 1.
  - **Normalization**: Scale data between 0 and 1.

## 3. **Encoding Categorical Data**
- **Methods**: 
  - **Label Encoding**: Convert categories to numbers.
  - **One-Hot Encoding**: Create binary columns for each category.

## 4. **Handling Outliers**
- **Methods**:
  - Remove outliers using statistical methods (IQR, Z-score).
  - Transform data using log transformations.

## 5. **Feature Engineering**

- **Methods**:
  - Create new features based on existing ones (e.g., extracting year from date).
  - Polynomial features to capture higher-order relationships.

## 6. **Splitting the Data**

- **Methods**:
  - **Train-Test Split**: Split data into training and test sets (e.g., 80/20).
  - **Cross-Validation**: Use k-fold cross-validation for more reliable evaluation.

## 7. **Text Preprocessing**

- **Methods**:
  - Tokenization, removing stop words, stemming/lemmatization.
  - Vectorization (TF-IDF, Bag of Words, Word2Vec).
