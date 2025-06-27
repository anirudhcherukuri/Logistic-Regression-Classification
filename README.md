#  Task 4: Logistic Regression Classification

##  **Objective**

Build a **binary classification model** using **Logistic Regression** to classify **breast cancer tumors as malignant or benign** based on features.

## 🛠️ **Tools Used**

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

##  **Dataset**

- **Name:** Breast Cancer Wisconsin Dataset
- **Source:** [UCI / Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Target column:** `diagnosis` (`M`=Malignant, `B`=Benign)

##  **Steps Performed**

1. **Imported libraries** (pandas, numpy, sklearn, matplotlib).
2. **Loaded dataset** and dropped irrelevant columns (`id`, `Unnamed: 32`).
3. **Encoded target column** (`diagnosis`) to binary (M=1, B=0).
4. **Checked and imputed missing values**.
5. **Split dataset** into train and test sets (80/20 split).
6. **Standardized features** using `StandardScaler`.
7. **Trained Logistic Regression model** on training data.
8. **Predicted** on test data.
9. **Evaluated performance** using:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC Score
10. **Plotted ROC Curve** for model evaluation.
11. **Plotted Sigmoid function** for conceptual understanding.

---

##  **Results**

| Metric            | Value |
|-------------------|-------|
| **Precision**     | *Add your output here* |
| **Recall**        | *Add your output here* |
| **ROC-AUC Score** | *Add your output here* |



##  **Sample Plots**

###  **ROC Curve**
*(Insert saved ROC curve image if pushed separately)*

###  **Sigmoid Function**
*(Insert saved sigmoid function plot if pushed separately)*

---

##  **How to Run**

1. Clone this repository:
    ```bash
    git clone <repo-link>
    cd <repo-folder>
   
2. Install dependencies:
    ```bash
    pip install pandas numpy scikit-learn matplotlib
  
3. Run the notebook:
    - Open `task4_logistic_regression.ipynb` in VS Code or Jupyter.
    - Execute cells sequentially.

##  **Key Learnings**

- Understanding of **Logistic Regression** for classification.  
- Importance of **standardizing features** before model fitting.  
- Use of **evaluation metrics** (precision, recall, ROC-AUC) for model assessment.  
- **Sigmoid function interpretation** as probability output in logistic regression.

