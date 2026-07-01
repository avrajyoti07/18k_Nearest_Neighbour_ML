# K-Nearest Neighbour (KNN) — Iris Classification

A beginner-friendly implementation of the **K-Nearest Neighbour (KNN)** algorithm to classify iris flowers into their respective species using `scikit-learn`. This project walks through the complete machine learning workflow — from loading and exploring data to training a model and evaluating its performance.

## 📌 Overview

This notebook demonstrates how KNN, a simple yet powerful supervised learning algorithm, can be used to solve a multi-class classification problem. The classic **Iris dataset** is used, where the goal is to predict the species of a flower (*Setosa*, *Versicolor*, or *Virginica*) based on its sepal and petal measurements.

## 📊 Dataset

The project uses the built-in **Iris dataset** from `sklearn.datasets`, which contains:
- **150 samples** across 3 flower species
- **4 features**: sepal length, sepal width, petal length, petal width (all in cm)
- **Target**: flower species (0 = Setosa, 1 = Versicolor, 2 = Virginica)

## 🛠️ Tech Stack

- Python 3
- pandas
- matplotlib
- seaborn
- scikit-learn

## 🔍 Workflow

1. **Load the data** — Import the Iris dataset and convert it into a pandas DataFrame.
2. **Explore the data** — Add target labels and flower names; inspect samples for each class.
3. **Visualize** — Scatter plots comparing sepal and petal dimensions across the three species to observe class separability.
4. **Train/Test Split** — Split the dataset into training (80%) and testing (20%) sets.
5. **Train the model** — Fit a `KNeighborsClassifier` (with `n_neighbors=10`) on the training data.
6. **Evaluate** — Measure accuracy on the test set, and generate a confusion matrix and classification report (precision, recall, F1-score) to assess performance in detail.

## 📈 Results

The trained KNN model is evaluated using:
- **Accuracy score** on the test set
- **Confusion matrix** (visualized as a heatmap using seaborn)
- **Classification report** showing precision, recall, and F1-score per class

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas matplotlib seaborn scikit-learn jupyter
```

### Running the notebook
```bash
git clone https://github.com/avrajyoti07/18k_Nearest_Neighbour_ML.git
cd 18k_Nearest_Neighbour_ML
jupyter notebook 17_K_Nearest_Neighbour.ipynb
```

## 📁 Repository Structure

```
18k_Nearest_Neighbour_ML/
│
├── 17_K_Nearest_Neighbour.ipynb   # Main notebook with EDA, training & evaluation
└── README.md                      # Project documentation
```

## 🧠 About KNN

K-Nearest Neighbour is a **lazy, instance-based learning algorithm** that classifies a new data point based on the majority class among its 'k' closest neighbours in the feature space. It requires no explicit training phase, making it simple to understand and implement, though it can be computationally expensive on large datasets.

## 📄 License

This project is open source and available for learning purposes.

## 👤 Author

**avrajyoti07**
