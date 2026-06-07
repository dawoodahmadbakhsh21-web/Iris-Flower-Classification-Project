# 🌸 Iris Flower Classification

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Sklearn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Models](https://img.shields.io/badge/Models-5-purple)
![Accuracy](https://img.shields.io/badge/Accuracy-97%25+-brightgreen)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

Multiclass classification on the classic Iris dataset using 5 machine learning models with cross-validation comparison and an interactive prediction widget.

---

## 📊 Dataset
- **Source:** Scikit-Learn built-in (`load_iris`)
- **Size:** 150 samples — 50 per class
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
- **Classes:** Setosa, Versicolor, Virginica

---

## 🔍 Key EDA Insights
- **Setosa** is linearly separable from the other two classes
- **Petal Length & Width** are the most discriminative features
- **Versicolor & Virginica** overlap slightly — harder to separate

---

## 🤖 Model Comparison
| Model | Test Accuracy | CV Mean | CV Std |
|-------|--------------|---------|--------|
| k-NN ✅ | 0.9333 | 0.9667 | 0.0312 |
| SVM | 0.9667 | 0.9667 | 0.0312 |
| Decision Tree | 0.9333 | 0.9417 | 0.0204 |
| Random Forest | 0.9000 | 0.9500 | 0.0167 |
| Gradient Boosting | 0.9667 | 0.9583 | 0.0264 |

**Best Model: k-NN** selected by 5-fold Cross Validation mean score.

---

## 📈 Visualizations

### Feature Distribution
![Boxplot](eda_boxplot.png)

### Pairplot
![Pairplot](eda_pairplot.png)

### Violin Plot
![Violin](eda_violin.png)

### Model Comparison
![Models](model_comparison.png)

### Confusion Matrices
![Confusion](confusion_matrices.png)

### Decision Tree
![Tree](decision_tree.png)

---

## 🗂️ Project Structure
```
iris-flower-classification/
├── iris_classification.ipynb
├── iris_project/
│   ├── iris_model.pkl
│   ├── scaler.pkl
│   └── model_meta.json
├── eda_boxplot.png
├── eda_pairplot.png
├── eda_violin.png
├── eda_heatmap.png
├── model_comparison.png
├── confusion_matrices.png
├── decision_tree.png
└── README.md
```

## 🚀 How to Run
1. Clone the repo
2. Open `iris_classification.ipynb` in Google Colab
3. Run all cells — no Kaggle setup needed!
4. Use the interactive sliders to predict any flower species

## 🛠️ Tech Stack
- Python 3.10
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-Learn (k-NN, SVM, Decision Tree, Random Forest, Gradient Boosting)
- ipywidgets (Interactive UI)

## 👤 Author
**Your Name** — [GitHub](https://github.com/yourusername) | [LinkedIn](https://linkedin.com/in/yourusername)
