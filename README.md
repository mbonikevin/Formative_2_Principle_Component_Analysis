# Formative 2 - Principle Component Analysis

This repository contains a Python implementation of **Principal Component Analysis (PCA)** from scratch using **NumPy**

The code demonstrates:

- Standardizing datasets
- Computing covariance matrices
- Eigendecomposition for PCA
- Sorting principal components
- Projecting data onto selected components
- Dynamic selection of components based on explained variance
- Performance considerations for larger datasets

The implementation does **not** use scikit-learn or any other PCA library.  

---

## Installation

1. Make sure you have **Python 3.8+** installed.
2. Clone this repository:
```bash
git clone https://github.com/mbonikevin/Formative_2_Principle_Component_Analysis.git
cd Formative_2_Principle_Component_Analysis
````

3. Install the required Python libraries:

```bash
pip install numpy matplotlib pandas
```

---

## Usage

1. Open the notebook `Mbonimpaye_Kaneza_Kevin_Formative2.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Upload the data set (found in data folder)
3. Run each cell step-by-step:

   * Loading and Preparing the Data
   * Step 1: Step 1: Load and Standardize the Data
   * Step 3: Calculate the Covariance Matrix
   * Step 4: Perform Eigendecomposition
   * Step 5: Sort Principal Components
   * Step 6: Project Data onto Principal Components
   * Step 7: Output the Reduced Data
   * Step 8: Visualize Before and After PCA
   * Task 2: Dynamically select the number of principal components based on explained variance.
   * Task 3: Performance Optimization and Scalability

4. The notebook will display:

   * Standardized Data
   * Covariance matrix
   * Eigenvalues and eigenvectors
   * Reduced data
   * Visualizations before and after PCA
   * Explained Variance and Component Selection
   * Performance Metrics

---

## Notes

* You can change the **variance threshold** in the notebook to select more or fewer principal components.

---

## Author

Kevin Kaneza Mbonimpaye\
Advanced Linear Algebra – PCA Formative Assignment