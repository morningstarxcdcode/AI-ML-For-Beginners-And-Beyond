# Matplotlib and Seaborn Cheatsheet

## Matplotlib Basics

- **Import Matplotlib**: `import matplotlib.pyplot as plt`
- **Create Line Plot**: `plt.plot(x, y)`
- **Add Labels**: `plt.xlabel('X-axis')`, `plt.ylabel('Y-axis')`
- **Add Title**: `plt.title('Title')`
- **Show Plot**: `plt.show()`
- **Save Plot**: `plt.savefig('plot.png')`

## Seaborn Basics

- **Import Seaborn**: `import seaborn as sns`
- **Create Scatter Plot**: `sns.scatterplot(x='col1', y='col2', data=df)`
- **Create Histogram**: `sns.histplot(data=df['column'])`
- **Create Heatmap**: `sns.heatmap(data.corr(), annot=True)`
- **Set Style**: `sns.set_style('darkgrid')`

## Common Operations

- **Customize Plot Size**: `plt.figure(figsize=(10, 6))`
- **Add Legend**: `plt.legend(['Label1', 'Label2'])`
- **Combine Matplotlib and Seaborn**: Use Seaborn for styling and Matplotlib for fine-tuning.

---
