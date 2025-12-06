  Credit Card Fraud Detection (Machine Learning)

This project builds a machine learning model to detect fraudulent credit card transactions.  
The dataset is highly imbalanced, so both undersampling and SMOTE oversampling were applied to improve fraud detection performance.

---

 Files in This Repository

| File | Description |
|------|-------------|
| `fraud_detection.ipynb` | Complete notebook (cleaning → balancing → models → selection → prediction) |
| `best_model.pkl` | Final selected fraud detection model |

>  Both notebook and model file are in the same location for ease of use.

---

 Dataset Access

The dataset used in this notebook can be downloaded from Kaggle:

🔗 https://www.kaggle.com/code/youssefelbadry10/credit-card-fraud-detection/input

Due to dataset size, it is not stored in this repository.  
Download and place it locally when running the notebook.

---

What the Notebook Includes

- Data loading and cleaning
- Feature engineering (datetime breakdown, encodings, etc.)
- Train–test split (80/20)
- Class imbalance treatment:
  - Random Undersampling
  - SMOTE Oversampling
- Model training for:
  - Decision Tree
  - Logistic Regression
  - Random Forest
- Detailed evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Best model selection logic:
  - Based on highest F1-score (primary)
- Saving final model as `best_model.pkl`
- Prediction on sample test cases (Fraud / Not Fraud + probability)

---

 Final Model

- **Random Forest**
- Selected based on best F1-score performance

