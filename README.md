# Industrial Failure Analysis and Prediction

## Project Overview

This project focuses on analyzing historical industrial maintenance data to understand failure behavior and explore how data-driven insights can support better decision-making.

The goal was not only to analyze the data, but also to apply machine learning techniques to identify patterns and explore future trends.

---

## Objectives

* Understand failure behavior over time
* Classify different types of failures
* Identify patterns in the data
* Estimate how failures may behave in the near future

---

## Dataset

The dataset comes from a real industrial maintenance environment.

Due to confidentiality reasons, it is not included in the repository. However, the full analysis can be followed in the notebook.

---

## Exploratory Data Analysis (EDA)

Before modeling, an exploratory analysis was performed to better understand the data:

* Checked for missing values
* Analyzed the distribution of failure types
* Explored how failures evolve over time

Key observations:

* There is a clear class imbalance between failure types
* Some categories appear significantly more frequently than others
* The behavior over time shows a relatively stable pattern

---

## Classification Model

A Random Forest model was used to classify different types of failures.

This model was chosen because it performs well with structured data and can capture non-linear relationships.

Results:

The model achieved an accuracy of around 60% in a multi-class problem with imbalanced data, which is a reasonable baseline for this type of scenario.

---

## Time Series Prediction

Prophet was used to forecast the future behavior of failures.

The model provides:

* A main prediction
* A lower bound (conservative scenario)
* An upper bound (optimistic scenario)

These predictions offer a general view of how failures might behave in the short term.

---

## Value of the Project

This type of analysis can help:

* Better understand equipment behavior
* Identify recurring failure patterns
* Anticipate potential issues
* Support maintenance decision-making
* Move from reactive to more predictive strategies

---

## Limitations

* The dataset is not included due to confidentiality
* Class imbalance affects model performance
* No advanced hyperparameter tuning was performed

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Prophet
* Matplotlib
* Jupyter Notebook / Google Colab

---

## Project Structure

* `industrial_failure_analysis_ml.ipynb` → full step-by-step analysis
* `predicciones_30_dias_todos_los_modos_fallo.xlsx` → prediction results

---

## Conclusion

This project represents a practical first step into working with real-world data and applying machine learning techniques.

Beyond the model itself, the most valuable part was the process of understanding the data, questioning it, and translating it into useful insights.
