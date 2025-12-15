# 🎗️ Breast Cancer Prediction using Binary Classification

This project contains a Jupyter Notebook implementing a supervised machine learning solution for **Binary Classification** to predict the status of a mass as either **Malignant** or **Benign**. It uses the popular **Breast Cancer Dataset** and demonstrates a complete classification pipeline, though it uniquely evaluates the results using standard **Regression Metrics** (MAE and MSE).

---

## 🎯 Project Goals

The objective is to train a classification model and evaluate its performance using common data science methodologies:

1.  **Data Preparation:** Load and inspect the structured medical dataset.
2.  **Model Training:** Train a suitable Scikit-learn classification algorithm (e.g., a simple linear model or tree-based model).
3.  **Prediction:** Generate class predictions on the test set.
4.  **Evaluation (Regression Metrics):** Calculate and report **Mean Absolute Error (MAE)** and **Mean Squared Error (MSE)** to quantify the average magnitude of error, which is an unconventional but informative way to assess a binary prediction model's performance on its 0/1 outputs. 

## 🗃️ Dataset Used

The model is designed for the **Breast Cancer Dataset** (often the Wisconsin Breast Cancer dataset, or similar), which typically includes features related to the characteristics of the cell nuclei (e.g., radius, texture, perimeter) and a binary target variable representing the diagnosis (Malignant or Benign).

## ⚙️ Technology Stack and Dependencies

The project is built on the standard Python data science stack, emphasizing metrics and data manipulation.

| Library | Role |
| :--- | :--- |
| **`pandas` & `numpy`** | Data loading, manipulation, and numerical operations. |
| **`scikit-learn`** | Core ML framework for model selection, data splitting, and calculating evaluation metrics (`mean_absolute_error`, `mean_squared_error`). |
| **`seaborn` & `plotly`** | Used for data visualization and inspection (implied). |

### Installation
```bash
pip install pandas numpy scikit-learn seaborn plotly

```bash
pip install pandas numpy scikit-learn seaborn plotly
