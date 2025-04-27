

# Data Analyst Internship – Day 5 Project

Welcome to Day 5 of the Data Analyst Internship!  
This project focuses on applying essential data exploration, cleaning, and basic modeling techniques on real-world datasets using Python.

## Project Overview

The Day 5 project covers the full lifecycle of preparing and analyzing a dataset:

- **Exploratory Data Analysis (EDA):**
  - Understanding the structure and distribution of data.
  - Identifying missing values, outliers, and data types.

- **Data Cleaning:**
  - Handling missing values appropriately.
  - Standardizing and scaling feature variables.
  - Saving scaling models for future use.

- **Descriptive Statistics:**
  - Generating summary statistics.
  - Visualizing distributions and relationships between variables using Matplotlib and Seaborn.

- **Feature Engineering:**
  - Separating independent and dependent variables.
  - Standardizing features with `StandardScaler`.

- **Model Building:**
  - Building a Logistic Regression model for binary classification.
  - Saving preprocessing tools (e.g., scaler) with compression (`bz2`, `pickle`).

- **Model Evaluation:**
  - Calculating R² score and Adjusted R² score to evaluate model performance.

This project combines EDA, cleaning, visualization, modeling, and evaluation into a complete workflow — similar to a real-world data analyst task.

---

## Topics Covered

- Exploratory Data Analysis (EDA)
- Handling missing values
- Data cleaning and preprocessing
- Descriptive statistics
- Data visualization basics (histograms, scatterplots)
- Feature scaling
- Logistic Regression modeling
- Model evaluation (R² and Adjusted R²)

---

## Requirements

- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - bz2
  - pickle

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Project Structure

```
project/
│
├──Dataset
├── notebook/
│   └── Logistic_regression.ipynb   # Full EDA, cleaning, modeling, evaluation
│
├──Licence              
│
├── README.md
```

- **notebook/**: Contains the Jupyter Notebook with complete code and visualizations.


---

## How to Run

1. Open `day5_data_analyst_project.ipynb` using Jupyter Notebook or VSCode.
2. Step through the EDA, cleaning, visualization, and model training cells.
3. Review model performance and understand insights from visualizations.

---

## Notes

- StandardScaler is saved separately to ensure consistent preprocessing on any new or unseen data.
- This project forms the foundation for more advanced analysis and machine learning pipelines in upcoming internship days.

---

## License

This project is intended for educational and internship learning purposes.

---

