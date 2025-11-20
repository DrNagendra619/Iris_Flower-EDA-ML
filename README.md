# Iris_Flower-EDA-ML
Iris_Flower EDA ML
# Iris Flower Classification: EDA and Machine Learning 🌸

## Overview

This repository contains a Jupyter Notebook that performs **Exploratory Data Analysis (EDA)** and implements **Machine Learning (ML)** models for the classic **Iris Flower Classification** task. The Iris dataset is a multivariate dataset used widely for introducing pattern recognition concepts and is foundational in machine learning.

The goal of this project is to:
1.  **Analyze** the distribution and relationships between the four primary features (sepal length, sepal width, petal length, and petal width).
2.  **Train and evaluate** multiple classification models to accurately predict the species of Iris flower (Setosa, Versicolor, or Virginica).

---

## Repository Files

| File Name | Description |
| :--- | :--- |
| `Iris_Flower EDA ML.ipynb` | The main Jupyter notebook containing all the steps for data loading, visualization (EDA), model training, and performance evaluation. |

---

## Dataset (Iris Flower Dataset)

The dataset contains **150 samples** across three species of Iris (50 samples per species). The four features used for classification are measured in centimeters:

| Feature | Unit |
| :--- | :--- |
| **Sepal Length** | cm |
| **Sepal Width** | cm |
| **Petal Length** | cm |
| **Petal Width** | cm |
| **Species (Target)** | Setosa, Versicolor, Virginica |

---

## Methodology and Results

### 1. Exploratory Data Analysis (EDA)

The notebook utilizes various visualizations to understand the data structure:

* **Histograms/KDE Plots:** To check the distribution of individual features.
* **Box Plots/Violin Plots:** To compare feature distributions across different species.
* **Scatter Plots/Pair Plots:** To visualize the correlation and separation boundaries between pairs of features, which helps in model selection. **Petal length and Petal width** typically show the strongest separation between species.

### 2. Machine Learning Classification

The following models are typically trained and evaluated for this classification task (based on standard practice with this dataset):

* **Model Training:** The data is split into training and testing sets (e.g., 80/20 split).
* **Evaluation Metrics:** Model performance is primarily measured using **Accuracy Score**, **Confusion Matrix**, and **Classification Reports**.

*(The specific models implemented in the notebook would determine the exact performance table, but common ones include:)*

| Model | Typical Test Accuracy |
| :--- | :--- |
| **K-Nearest Neighbors (KNN)** | ~93% - 98% |
| **Support Vector Machine (SVM)** | ~95% - 100% |
| **Decision Tree / Random Forest** | ~93% - 98% |
| **Logistic Regression** | ~90% - 97% |

**Key Finding:** The highest accuracy is usually achieved by models like **SVM** or **KNN**, demonstrating excellent separability between the Iris species, particularly when considering petal measurements.

---

## Usage and Setup

To run this analysis locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    cd [Your Repository Name]
    ```

2.  **Install dependencies:**
    The notebook requires standard Python data science libraries:
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```

3.  **Launch Jupyter:**
    ```bash
    jupyter notebook
    ```
    Open the `Iris_Flower EDA ML.ipynb` file to run the code and view the interactive analysis and results.
