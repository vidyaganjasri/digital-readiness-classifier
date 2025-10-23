

# Classification Modeling Project: Predicting DRS Outcome

## Project Overview

The core goal of this project was to develop a **robust and highly accurate classification model** to predict the target variable, **DRS**, using key socio-economic indicators such as Education Attainment Index (%) and Internet Penetration (%). The entire process, from data assessment to final validation, was driven by the principle of selecting a model best suited to the data's inherent structure.

---

## Methodology: From Data Structure to Final Model

### 1. Data Assessment & Non-Linearity Confirmation

The initial and most crucial step was determining the fundamental relationship within the data.

* **Visualization Insight:** Initial scatter plots showed that data points were grouped into **distinct, separate clusters** (e.g., low-DRS and high-DRS groups) rather than following a continuous line.
* **Conclusion:** This clustering definitively indicated a **non-linear** relationship, which immediately guided us away from simpler linear models and toward more powerful non-linear algorithms.

### 2. Model Selection and Benchmarking

Based on the confirmed non-linearity, we focused on benchmarking four prominent non-linear classification models:

* **Models Tested:** Random Forest, Gradient Boosting, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN).
* **Result:** The **Random Forest Classifier** emerged as the top performer, achieving the highest initial accuracy and the most balanced performance across all evaluation metrics.

### 3. Rigorous Validation and Generalization

The Random Forest model was then subjected to rigorous checks to ensure its reliability and generalizability.

#### **A. 5-Fold Cross-Validation**
* We utilized **5-fold Cross-Validation** as a crucial validation methodology to test the model's **stability**.
* The scores were highly consistent across all five folds, confirming the model's performance is **stable and robust**, not dependent on a specific data split, thereby proving its effectiveness for real-world predictions.

---

---

## Final Conclusion

The **Random Forest Classifier** was selected as the final model due to its superior handling of the data's non-linear, clustered structure. Its performance was confirmed to be both **highly accurate and well-generalized** through a thorough validation process.
