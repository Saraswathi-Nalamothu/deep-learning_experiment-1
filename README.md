# Single Layer Perceptron for Binary Classification

## Overview

This repository contains the implementation of **Experiment 1** for the **Deep Learning Laboratory (CS3807)** at **Shiv Nadar University Chennai**.

The objective of this experiment is to understand the working of an Artificial Neuron and implement a **Single Layer Perceptron from scratch** for binary classification. The implementation includes dataset preprocessing, exploratory data analysis, perceptron training using the perceptron learning rule, performance evaluation, and comparison of different learning rates.

---

## Experiment Details

- **Course:** CS3807 – Deep Learning Laboratory
- **Experiment:** 1
- **Title:** Implementation of a Single Layer Perceptron for Binary Classification
- **Academic Year:** 2026–27

---

## Objectives

- Understand the architecture of a Single Layer Perceptron.
- Implement the Perceptron Learning Algorithm from scratch.
- Perform Exploratory Data Analysis (EDA).
- Normalize the dataset.
- Train the perceptron using the learning rule.
- Evaluate the classifier using standard performance metrics.
- Study the effect of different learning rates.

---

## Dataset

**Dataset Name:** Banknote Authentication Dataset

**Source:**
UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/267/banknote+authentication

### Dataset Information

| Attribute | Value |
|-----------|--------|
| Instances | 1372 |
| Features | 4 Numerical Features |
| Classes | 2 |
| Missing Values | None |
| Task | Binary Classification |

### Features

- Variance
- Skewness
- Curtosis
- Entropy

### Target Classes

- **0** – Authentic Banknote
- **1** – Forged Banknote

---

## Project Workflow

1. Dataset Loading
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Normalization
5. Train-Test Split
6. Single Layer Perceptron Implementation
7. Model Training
8. Performance Evaluation
9. Learning Rate Analysis

---

## Exploratory Data Analysis

The following visualizations were generated during EDA:

- Histogram of Variance
- Histogram of Skewness
- Histogram of Curtosis
- Histogram of Entropy
- Correlation Heatmap
- Scatter Plot
- Boxplot of Variance
- Boxplot of Skewness
- Boxplot of Curtosis
- Boxplot of Entropy

---

## Training Visualizations

The training process includes the following plots:

- Training Error vs Epoch
- Weight Evolution
- Bias Evolution
- Learning Rate Comparison
- Confusion Matrix

---

## Performance Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## Repository Structure

```
Single-Layer-Perceptron/
│
├── Dataset/
│   └── data_banknote_authentication.csv
│
├── Images/
│   ├── Histogram_Variance.png
│   ├── Histogram_Skewness.png
│   ├── Histogram_Curtosis.png
│   ├── Histogram_Entropy.png
│   ├── Correlation_Heatmap.png
│   ├── Scatter_Plot.png
│   ├── Boxplot_Variance.png
│   ├── Boxplot_Skewness.png
│   ├── Boxplot_Curtosis.png
│   ├── Boxplot_Entropy.png
│   ├── Training_Error_vs_Epoch.png
│   ├── Weight_Evolution.png
│   ├── Bias_Evolution.png
│   ├── Confusion_Matrix.png
│   └── Learning_Rate_Comparison.png
│
├── Experiment_1_Perceptron.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the notebook using:

- Google Colab
- Jupyter Notebook

Execute the cells sequentially.

---

## Learning Rates Used

- 0.001
- 0.01
- 0.1

The effect of each learning rate on convergence was analyzed and compared.

---

## References

1. Frank Rosenblatt, *The Perceptron*, Psychological Review, 1958.

2. Ian Goodfellow, Yoshua Bengio, Aaron Courville, *Deep Learning*, MIT Press, 2016.

3. C. M. Bishop, *Pattern Recognition and Machine Learning*, Springer.

4. S. Haykin, *Neural Networks and Learning Machines*, Pearson.

5. UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/267/banknote+authentication

6. Scikit-learn Documentation

https://scikit-learn.org/

---

## Author

**Saraswathi Nalamothu**

B.Tech Artificial Intelligence & Data Science

Shiv Nadar University Chennai

Academic Year: 2026–27
