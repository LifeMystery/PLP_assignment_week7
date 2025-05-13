# Iris Dataset Analysis with Pandas and Matplotlib

## 📋 Objective
This project demonstrates how to:
- Load and explore a dataset using the `pandas` library in Python.
- Perform basic data analysis such as statistical summaries and groupings.
- Visualize results using `matplotlib` and `seaborn`.

---

## 📁 Files Included
- `iris_analysis.ipynb` or `iris_analysis.py`: Main analysis script containing all tasks.
- `README.md`: Project overview and instructions.

---

## 📊 Dataset Description
The dataset used is the **Iris dataset**, a classic dataset in machine learning that includes:
- 150 samples of iris flowers
- 4 numerical features: sepal length, sepal width, petal length, petal width
- 3 species: *setosa*, *versicolor*, and *virginica*

This dataset is loaded directly using `sklearn.datasets.load_iris()`.

---

## ✅ Tasks Performed

### Task 1: Load and Explore the Dataset
- Loaded the Iris dataset using `sklearn`
- Converted to a `pandas` DataFrame
- Checked for missing values and data types

### Task 2: Basic Data Analysis
- Calculated mean, median, standard deviation using `.describe()`
- Grouped data by species and computed average petal length
- Observed patterns across species

### Task 3: Data Visualization
Created 4 types of plots:
1. **Line Chart** – Sepal length over sample index
2. **Bar Chart** – Average petal length by species
3. **Histogram** – Distribution of sepal width
4. **Scatter Plot** – Sepal length vs. petal length colored by species

---

## 📌 Requirements
To run this project, install the following Python libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
