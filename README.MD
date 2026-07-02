## 📊 Project Visualizations

### Feature Importance
The Random Forest model identified the most influential variables contributing to diabetic patient readmission prediction.

![Feature Importance](feature_importance.png)

---

### Random Forest Confusion Matrix
The confusion matrix summarizes the model's prediction performance by comparing actual and predicted readmission outcomes.

![Confusion Matrix](confusion_matrix.png)

---

### ROC Curve
The ROC curve evaluates the model's ability to distinguish between readmitted and non-readmitted patients. The model achieved an ROC-AUC score of **0.660**, indicating moderate predictive performance.

![ROC Curve](roc_curve.png)

---

### Sample Decision Tree
A representative decision tree from the Random Forest model illustrating how diagnosis, medication, and demographic features contribute to prediction decisions.

![Decision Tree](decision_tree.1.png)

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Machine Learning
- Healthcare Analytics

# Predicting 30-Day Hospital Readmission Risk Among Diabetic Patients Using Machine Learning

## Objective
Develop predictive machine learning models to identify diabetic patients at risk of hospital readmission within 30 days.

## Dataset
- 101,766 patient encounters
- 50 variables
- Target:
  - 1 → Readmitted within 30 days
  - 0 → Not Readmitted

## Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC–AUC

## Key Findings
- Logistic Regression identified more readmission cases
- Random Forest achieved higher overall accuracy
- ROC-AUC = 0.660 indicating moderate predictive ability

## Clinical Impact
Predictive analytics can support early identification of high-risk diabetic patients and improve care coordination.

## Tech Stack
Python • Pandas • NumPy • Scikit-Learn • Matplotlib

## Repository Structure
- Diabetics_final.ipynb
- diabetic_data.csv
- README.md
