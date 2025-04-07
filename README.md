
# 🧠 Breast Cancer Classifier

This project compares various machine learning algorithms to diagnose **breast cancer**. The dataset used is the Wisconsin Breast Cancer Diagnostic Dataset (WBCD).

## 🔍 Objective

To classify tumors as **benign** or **malignant** based on microscopic features of cell nuclei.

## 📁 Project Structure

```
breast-cancer-classifier/
│
├── data/
│   └── data.csv              # Original dataset
│
├── models/
│   ├── logistic_regression.py
│   ├── knn.py
│   ├── svm.py
│   └── random_forest.py      # Different classifiers
│
├── README.md                 # Project overview (this file)
└── requirements.txt          # Required packages
```

## ⚙️ Algorithms Used

- ✔️ Logistic Regression
- ✔️ K-Nearest Neighbors (KNN)
- ✔️ Support Vector Machines (SVM)
- ✔️ Random Forest (optional)

## 📊 Dataset Info

- **Source**: UCI Machine Learning Repository
- **Number of Features**: 30 numerical attributes
- **Target Variable**: `diagnosis`
  - `M`: Malignant
  - `B`: Benign

## 🚀 How to Run

1. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. To run the logistic regression model, for example:
   ```bash
   python models/logistic_regression.py
   ```

## 📈 Model Performance

Each model prints its test accuracy at the end. You can compare performance across classifiers.

## 🧪 Potential Enhancements

- Evaluate with ROC-AUC scores
- Use GridSearch for hyperparameter tuning
- Compare models visually using plots or summary tables

## 📬 Contact

For questions or contributions: [yasar@example.com] (or link to GitHub profile)
