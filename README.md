# Pocket Algorithm with Linear Classifier on UCI Breast Cancer Dataset

## 1. What problems did you finish?
- **Problem 1:**
Performed Exploratory Data Analysis (EDA) and Data Transformation (DT), including visualization of class balance, feature ranges, and correlations. Applied train-only feature standardization using `StandardScaler`.
  
- **Problem 2:**
Initialized the model weights \( w_0 \) using Linear Regression via the Moore–Penrose pseudoinverse (`numpy.linalg.pinv`).
  
- **Problem 3:**
Implemented a fully vectorized **Pocket Algorithm** that updates weights for misclassified samples and “pockets” the best-performing weights.
  
- **Problem 4:**
Designed and executed 10 randomized, stratified trials for each training set size \( N \in \{50, 100, 150, 200, 250, 300, 350, 400, 450, 500\} \), keeping 100 samples fixed for testing.
  
- **Problem 5:** Computed and analyzed key metrics — \(E_{in}\), \(E_{out}\), generalization gap, and average updates — along with visualizations (EDA summary and 2×2 results panel).


## 2. What platform did you use?
The Pocket Algorithm implementation was developed and executed using Python with scikit-learn in Google Colab.



## 3. Resources That Helped Me

- [Scikit-learn Documentation — Breast Cancer Dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset)  
- [NumPy Documentation — `np.linalg.pinv`](https://numpy.org/doc/stable/reference/generated/numpy.linalg.pinv.html)  
- [Matplotlib Documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)  
- [Colab + GitHub Integration Guide](https://colab.research.google.com/github)  
- [Pocket Algorithm for Training Perceptrons — StackExchange Discussion](https://stats.stackexchange.com/questions/51200/pocket-algorithm-for-training-perceptrons) 

