
# Customer Churn Prediction

## Project Overview
This project predicts customer churn for a telecom company using the Telco Customer dataset.  
We experimented with multiple models including Logistic Regression, Random Forest, and XGBoost.  
The final model is a tuned Random Forest classifier trained on a balanced dataset using SMOTE.

---

## Models and Performance

| Model                            | Accuracy | Precision | Recall | F1 Score |
|---------------------------------|----------|-----------|--------|----------|
| Logistic Regression (Baseline)   | 0.7896   | 0.6242    | 0.5241 | 0.5698   |
| Random Forest (Basic)            | 0.7846   | 0.6220    | 0.4840 | 0.5444   |
| XGBoost                         | 0.7740   | 0.5909    | 0.4866 | 0.5337   |
| Random Forest + Tuning + SMOTE   | 0.7612   | 0.5399    | 0.6872 | 0.6047   |

---

## Key Features
- Payment method (Electronic check)
- Tenure (Length of service)
- Total charges
- Monthly charges
- Fiber optic internet service
- Contract type (One year, Two year)
- Paperless billing

---

## Methodology
1. **Data Preprocessing**: Handling missing values and one-hot encoding categorical variables.  
2. **Baseline Modeling**: Logistic Regression as a starting point.  
3. **Advanced Modeling**: Random Forest and XGBoost models trained and compared.  
4. **Data Balancing**: SMOTE oversampling to handle class imbalance.  
5. **Hyperparameter Tuning**: GridSearchCV to optimize Random Forest parameters.  
6. **Feature Importance Analysis**: Identifying features that most influence churn.

---

## Tools and Libraries
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)  
- imbalanced-learn (SMOTE)  
- XGBoost

---

## How to Run
1. Install requirements:  
```bash
pip install -r requirements.txt
```
2. Run the Jupyter notebook `notebook.ipynb` or the Python script.  
3. Explore the results and visualization outputs.

---

## Author
Leila Ghasemzadeh  
LinkedIn: [your-linkedin]  
GitHub: [your-github]

---

## License
MIT License
