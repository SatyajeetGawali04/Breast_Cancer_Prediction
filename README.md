# Breast Cancer Prediction Using Machine Learning

A machine learning project designed to classify breast tumors as **Benign** or **Malignant** based on cellular attributes from clinical diagnostic data.

---

## 📌 Problem Statement & Business Objective

- **Problem Statement:** Breast cancer is one of the most common cancers affecting individuals worldwide. Early and precise diagnosis significantly improves treatment success and patient survival rates.
- **Business Objective:** Develop an accurate machine learning classification model to assist healthcare professionals in identifying malignant tumors at an early stage.

---

## 📊 Dataset Description

The dataset `Dataset/BreastCancer.csv` contains clinical samples with the following features:

| Feature Name | Description |
|---|---|
| `Id` | Sample identifier |
| `Cl.thickness` | Clump Thickness (1 - 10) |
| `Cell.size` | Uniformity of Cell Size (1 - 10) |
| `Cell.shape` | Uniformity of Cell Shape (1 - 10) |
| `Marg.adhesion` | Marginal Adhesion (1 - 10) |
| `Epith.c.size` | Single Epithelial Cell Size (1 - 10) |
| `Bare.nuclei` | Bare Nuclei (1 - 10) |
| `Bl.cromatin` | Bland Chromatin (1 - 10) |
| `Normal.nucleoli` | Normal Nucleoli (1 - 10) |
| `Mitoses` | Mitoses (1 - 10) |
| `Class` | Target Diagnosis (`benign` / `malignant`) |

---

## 📈 Exploratory Data Analysis & Visualizations

### 1. Feature Correlation Heatmap
![Correlation Heatmap](Results/Corelation%20Heatmap.png)

### 2. Feature Importance
![Feature Importance](Results/Feature%20Importance.png)

---

## 🤖 Model Training & Hyperparameter Tuning

Multiple Machine Learning models were evaluated:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**

Hyperparameter tuning was conducted using `GridSearchCV` to optimize classification metrics.

### Best Parameters & Hyperparameter Optimization
![Best Parameter](Results/Best%20Parameter.png)

---

## 📊 Results & Performance Evaluation

### Model Comparison
![Model Comparison](Results/Model%20Comparison.png)

### ROC AUC Curves
![ROC Curve](Results/ROC%20Curve.png)

---

## 📁 Directory Structure

```
Breast_Cancer_Prediction/
│
├── Dataset/
│   └── BreastCancer.csv
│
├── Jupyter Notebook/
│   └── Breast_Cancer_Prediction.ipynb
│
├── ReadMe/
│   └── Breast Cancer Prediction Using Machine Learning ReadMe.docx
│
├── Results/
│   ├── Best Parameter.png
│   ├── Corelation Heatmap.png
│   ├── Feature Importance.png
│   ├── Model Comparison.png
│   └── ROC Curve.png
│
└── README.md
```

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SatyajeetGawali04/Breast_Cancer_Prediction.git
   cd Breast_Cancer_Prediction
   ```

2. **Install required dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook "Jupyter Notebook/Breast_Cancer_Prediction.ipynb"
   ```

---

## 👤 Author
- **Satyajeet Gawali** ([GitHub Profile](https://github.com/SatyajeetGawali04))
