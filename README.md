# svm-kernel-tutorial
SVM Kernel comparison using Linear, Polynomial and RBF kernels on Pima Diabetes dataset
# SVM Kernel Comparison on Pima Indians Diabetes Dataset


## 👤 Author

Polimetla Surya Teja
Student Number: 24164403

## 📌 Overview
This project explores the performance of different Support Vector Machine (SVM) kernels:
- Linear Kernel
- Polynomial Kernel
- Radial Basis Function (RBF) Kernel

The objective is to understand how kernel choice affects classification performance and decision boundaries using a real-world medical dataset.

---

## 📊 Dataset
The dataset used is the **Pima Indians Diabetes Dataset**, which is widely used for binary classification problems.

- Total samples: 768  
- Features: 8 numerical input features  
- Target: Binary (0 = No Diabetes, 1 = Diabetes)  

---

## ⚙️ Methods Used

- **StandardScaler** → Feature normalization  
- **Support Vector Machine (SVC)** → Classification model  
- **GridSearchCV** → Hyperparameter tuning  
- **Cross-validation (5-fold)** → Model evaluation  

---

## 🔍 Models Compared

### 1. Linear Kernel
- Simple, fast, and interpretable  
- Works well for linearly separable data  

### 2. Polynomial Kernel
- Captures curved relationships  
- Performance depends on degree  

### 3. RBF Kernel
- Highly flexible  
- Captures complex, non-linear patterns  

---

## 📈 Results

| Kernel     | Train Accuracy | Test Accuracy |
|------------|----------------|---------------|
| Polynomial | 0.75           | 0.736         |
| RBF        | 0.79           | 0.758         |
| Linear     | 0.78           | 0.749         |

👉 The **RBF kernel achieved the highest test accuracy**, indicating better generalization performance.

---

## 📷 Visualizations

The project includes:

- Decision boundary plots for each kernel  
- Accuracy comparison graph  

Example:

- RBF kernel shows a flexible boundary adapting to non-linear data  
- Linear kernel produces a straight decision boundary  
- Polynomial kernel creates curved boundaries  

---

##🎯 Key Insights

- Kernel choice significantly impacts SVM performance
- RBF kernel performs best for non-linear datasets
- Linear kernel works well for simpler patterns
- Polynomial kernel requires careful tuning
  
  
---

##📚 References

- Cortes, C., & Vapnik, V. (1995). Support-vector networks. Machine Learning
- Towards Data Science – SVM Explained

  
---

## ▶️ How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/Suryaaaaa9999/svm-kernel-tutorial.git
pip install numpy pandas matplotlib scikit-learn
notebook/ML_SVM.ipynb

svm-kernel-tutorial/
│
├── README.md
├── LICENSE
│
├── data/
│   └── pima-indians-diabetes.csv
│
├── notebook/
│   └── svm_model.ipynb
│
├── report/
│   └── svm_report.pdf
│
├── images/
│   ├── accuracy.png
│   ├── rbf.png
│   ├── linear.png
│   └── poly.png





