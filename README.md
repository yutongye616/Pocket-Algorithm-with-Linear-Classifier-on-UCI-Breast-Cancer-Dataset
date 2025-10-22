# Pocket Algorithm with Linear Classifier on UCI Breast Cancer Dataset

## 1️⃣ What Did You Finish?

I completed an end-to-end implementation of the **Pocket Algorithm** — a modification of the classical Perceptron that stores the “best” weights during training.  
This experiment was run on the **UCI Breast Cancer Wisconsin Dataset** to analyze the effects of **feature standardization** on optimization speed, accuracy, and generalization.

### Key Features Implemented:
- Linear Regression initialization using the **Moore–Penrose Pseudoinverse**
- Pocket Algorithm with random misclassified sample updates
- Comparative experiments **with and without feature standardization**
- Visualizations for:
  - In-sample vs. Out-of-sample error  
  - Generalization gap  
  - Convergence speed  
  - Final test error comparison
- 10 randomized trials per sample size to ensure reliability  

The study clearly showed that **standardization improves convergence, stability, and generalization**.  
Average convergence was **5× faster**, with **44% lower test error** compared to using raw features.

---

## 2️⃣ What Platform Did You Use?

- 💻 **Google Colab** (Python 3 environment)
- 🧠 Libraries used:
  - `NumPy`
  - `Matplotlib`
  - `scikit-learn`
- 🧭 Dataset: `sklearn.datasets.load_breast_cancer()`
- 🖥️ System: macOS (saved and synced to GitHub)

---

## 3️⃣ Resources That Helped Me

- [Scikit-learn Documentation — Breast Cancer Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset)
- [NumPy Documentation — `np.linalg.pinv`](https://numpy.org/doc/stable/reference/generated/numpy.linalg.pinv.html)
- [Matplotlib Documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
- [Colab + GitHub Integration Guide](https://colab.research.google.com/github)
- Blog: *“Pocket Algorithm Explained”* — CodeProject (2024)

---

### 🧩 Author
**Yutong Ye**  
*October 2025 — Queens College CS Program*  
📊 Exploring optimization, data preprocessing, and AI system reliability.
