# Handwritten Digit Recognition using Classical Machine Learning

This repository contains the implementation of a handwritten digit recognition system. The project focuses on building a complete machine learning pipeline using **classical ML algorithms**, without using any pre-trained models or neural networks.

The task involves classifying grayscale handwritten digit images (0–9) from an MNIST subset dataset provided in CSV format.

---

## How to Run

1. Clone the repository
2. Open the `.ipynb` file in Jupyter Notebook or Google Colab
3. Run all cells sequentially

## Dataset Information

The dataset used in this project is an MNIST subset provided in CSV format.

Due to GitHub file size limitations, the dataset is not included in this repository.

### How to Obtain the Dataset

You can download the MNIST CSV dataset from Kaggle:
- https://www.kaggle.com/competitions/digit-recognizer/data

After downloading, place the CSV file inside this `Data/` folder before running the notebook.

---

## Models Implemented

The following classical machine learning models were implemented and evaluated:

- **K-Nearest Neighbors (KNN)**
  - Raw features
  - PCA-reduced features
  - k tuned using elbow method

- **Support Vector Machine (SVM)**
  - Raw features
  - PCA-reduced features
  - C and gamma tuned manually

- **Decision Tree**
  - Raw features only
  - max_depth and min_samples_split tuned manually

- **From-Scratch Model**
  - KNN implemented using NumPy without ML training libraries

- **Ensemble Model (Bonus)**
  - Hard voting ensemble using KNN, SVM, and Decision Tree

---
