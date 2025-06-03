# 📍 Task 6: K-Nearest Neighbors (KNN) Classification

## 📌 Objective
The goal of this task is to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification. We'll use the **Iris Dataset** to explore how the choice of `K` impacts accuracy and visualize decision boundaries in 2D.

---

## 📁 Dataset
- **Name**: Iris Dataset
- **Source**: [UCI ML Repository / Scikit-learn built-in dataset](https://www.kaggle.com/datasets/uciml/iris)
- **Classes**: Setosa, Versicolor, Virginica
- **Features**: Sepal length, Sepal width, Petal length, Petal width

---

## 🛠️ Tools Used
- Python 3.x  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 🚀 Steps Performed

### 1. Load and Explore Dataset
- Used `load_iris()` from scikit-learn
- Checked shape, data types, and class distribution

### 2. Normalize Features
- Applied `StandardScaler` to scale features before training
- Normalization is important for distance-based models like KNN

### 3. Train-Test Split
- Data split: 70% training, 30% testing using `train_test_split`

### 4. Train KNN Models
- Trained models with `K` ranging from 1 to 10
- Tracked and plotted accuracy for each K value

### 5. Model Evaluation
- Selected best `K` based on highest test accuracy
- Evaluated with:
  - Confusion Matrix
  - Classification Report

### 6. Decision Boundary Visualization (Bonus)
- Plotted decision boundaries using the first two features
- Used `matplotlib` and `ListedColormap` for visualization

---

## 📈 Results

|    K      | Accuracy    |
|-----------|-------------|
|  K=1      |   ~0.98     |
|  K=2      |   ~0.98     |
|  K=3      |   ~1.00     |
|  K=4      |   ~0.98     | 
|  K=5      |   ~1.00     |
|  K=6      |   ~1.00     |
|  K=7      |   ~1.00     |
|  K=8      |   ~1.00     |
|  K=9      |   ~1.00     |
|  K=10     |   ~1.00     |

**Best K:** Usually around 3 or 5 depending on random seed

---

## ✅ Submitted by:MUMMADI RAMCHARAN

---


