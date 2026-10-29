# Outlier Detection using IQR in Python

A simple and practical Python notebook demonstrating how to detect statistical outliers using the **Interquartile Range (IQR)** method and visualize them with **Seaborn**.

## 📊 What's Inside?
- Calculating data quantiles ($Q_1, Q_3$, and Median) using `NumPy`.
- Calculating the **IQR** ($Q_3 - Q_1$).
- Setting lower and upper fences to identify anomalies:
  - $\text{lower\_fence} = Q_1 - 1.5 \times \text{IQR}$
  - $\text{upper\_fence} = Q_3 + 1.5 \times \text{IQR}$
- Visualizing outliers using a Seaborn **Boxplot**.

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Seaborn

## 🚀 How to Run
Open the `outliers.ipynb` file in Jupyter Notebook or JupyterLab to run the cells step by step.
