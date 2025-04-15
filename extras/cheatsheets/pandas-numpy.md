# Pandas and NumPy Cheatsheet

## Pandas Basics

- **Import Pandas**: `import pandas as pd`
- **Create DataFrame**: `df = pd.DataFrame(data)`
- **Read CSV**: `df = pd.read_csv('file.csv')`
- **Filter Rows**: `df[df['column'] > value]`
- **Basic Stats**: `df.describe()`

## NumPy Basics

- **Import NumPy**: `import numpy as np`
- **Create Array**: `arr = np.array([1, 2, 3])`
- **Array Shape**: `arr.shape`
- **Mean**: `np.mean(arr)`
- **Reshape Array**: `arr.reshape(rows, cols)`

## Common Operations

- **Merge DataFrames**: `pd.merge(df1, df2, on='key')`
- **Group By**: `df.groupby('column').mean()`
- **Matrix Multiplication**: `np.dot(arr1, arr2)`
- **Element-wise Operations**: `arr1 + arr2`
