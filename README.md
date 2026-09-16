# Python Data Analytics – Assignment 2
## Data Visualization Using Python

### 📌 Project Overview

This project focuses on **data cleaning, analysis, and visualization using Python**.

The project uses the **Seaborn Taxis dataset** to explore taxi trip information and create different types of visualizations using **Pandas, NumPy, Matplotlib, and Seaborn**.

The main objective is to understand the dataset, handle missing values, analyze relationships between variables, and represent the findings through meaningful visualizations.

---

## 🛠️ Technologies & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Dataset

The project uses the built-in **Taxis dataset** available in Seaborn.

The dataset contains information related to taxi trips, including:

- Pickup timestamp
- Dropoff timestamp
- Distance
- Fare
- Tip
- Tolls
- Total amount
- Payment method
- Pickup zone
- Pickup borough

Dataset loading:

```python
import seaborn as sns

df = sns.load_dataset("taxis")
