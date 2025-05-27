# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

This project is part of the AI & ML Internship Task 1, focusing on data cleaning and preprocessing using the Titanic dataset.

---

## 📝 Objective

To clean, preprocess, and prepare raw data for machine learning models by handling missing values, encoding categorical variables, scaling features, and detecting/removing outliers.

---

## 📂 Dataset

- **Name:** Titanic Dataset  
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File Used:** `Titanic-Dataset.csv`

---

## 🛠 Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn (for scaling)

---

## 🧪 Preprocessing Steps Performed

1. **Loaded Dataset**
   - Used Pandas to load and inspect the dataset.

2. **Explored Dataset**
   - Viewed data types, missing values, and statistical summaries.

3. **Handled Missing Values**
   - Filled missing `Age` with median.
   - Filled missing `Fare` with mean.
   - Dropped rows with missing `Embarked`.

4. **Encoded Categorical Features**
   - Applied one-hot encoding to `Sex` and `Embarked`.

5. **Scaled Numerical Features**
   - Used StandardScaler to normalize `Age` and `Fare`.

6. **Outlier Detection & Removal**
   - Used boxplots to visualize outliers.
   - Removed outliers using IQR (Interquartile Range) method.

---

## 📊 Visualizations

- Boxplots of `Age` and `Fare` to detect outliers.
- Bar plots for categorical value distributions.

---

## 📁 Files in This Repository

| File Name            | Description                                 |
|----------------------|---------------------------------------------|
| `Titanic-Dataset.csv`   | The raw Titanic dataset                    |
| `Task(1).ipynb`         | Jupyter notebook with all preprocessing steps |
| `README.md`             | This file describing the project           |

---

## 📌 What I Learned

- Data cleaning and feature engineering
- Handling missing data effectively
- Encoding techniques for categorical data
- Importance of feature scaling
- Detecting and removing outliers

---

## 🔗 Connect with Me

Feel free to reach out if you have any questions or suggestions!

