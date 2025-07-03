# KNN Classification with Iris Dataset 🌸

## 🎯 Objective
Implement and understand the K-Nearest Neighbors (KNN) algorithm for multi-class classification using the Iris dataset.

---

## 📊 Dataset Used
- **Name**: Iris Dataset
- **Source**: [Kaggle Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
- **Features**:
  - sepal length (cm)
  - sepal width (cm)
  - petal length (cm)
  - petal width (cm)
- **Target**: Species (Setosa, Versicolor, Virginica)

---

## 🧪 Steps Performed

1. Loaded dataset using `sklearn.datasets.load_iris()`
2. Normalized features using `StandardScaler`
3. Split data into training and test sets (80/20)
4. Trained multiple KNN models with different values of **K**
5. Evaluated performance using accuracy and confusion matrix
6. Visualized decision boundaries (using first 2 features)

---

## 📈 Results

| Metric             | Value         |
|--------------------|---------------|
| Best K             | *K = 6*       |
| Test Accuracy      | *0.97*        |
| Classes Predicted  | Setosa, Versicolor, Virginica |

---

## 💡 Key Learnings

- KNN is sensitive to scale → Normalization is essential.
- Lower K → More flexible but risk of overfitting.
- Higher K → Smoother boundary but may underfit.
- Best K is chosen using validation or accuracy comparison.

---

## 💬 Interview Questions Covered

- How does KNN work?
- How to choose the best K?
- Why normalization is important?
- KNN time complexity?
- Sensitivity to noise
- Role of distance metrics (e.g., Euclidean)
- Multi-class handling

---

