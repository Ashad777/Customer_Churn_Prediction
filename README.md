# Customer Churn Prediction using Random Forest Classifier

This project aims to predict customer churn using a **Random Forest Classifier**, helping businesses identify customers who are likely to leave their service. By understanding these patterns, companies can take proactive actions to retain valuable customers and reduce churn.

The dataset used includes customer demographics, account details, and usage data, such as age, gender, balance, estimated salary, and whether the customer has churned. The goal is to use this data to predict if a customer will churn (1) or stay (0).

## Key Steps Involved:
1. **Data Preprocessing:**
   - Unnecessary columns, such as `CustomerId`, `Surname`, and `RowNumber`, are removed.
   - Categorical features like `Gender` and `Geography` are encoded using label encoding.
   - A new feature, `Balance_salary_ratio`, is created by dividing the customer balance by their estimated salary.
   - The dataset is then split into training and testing sets to train and evaluate the model.

2. **Model Training:**
   - A **Random Forest Classifier** is chosen for its ability to handle both numerical and categorical data effectively. The classifier is trained on the processed data to learn patterns related to customer churn.

3. **Model Evaluation:**
   - The model is evaluated on the test set using various performance metrics like accuracy, precision, recall, and F1 score to measure its effectiveness in predicting churn.

4. **Prediction:**
   - Once trained, the model predicts whether a customer is likely to churn, providing businesses with actionable insights on customer retention.

## Libraries Used:
- **Pandas** for data manipulation.
- **Seaborn/Matplotlib** for data visualization.
- **Scikit-learn** for machine learning model building, training, and evaluation.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn
3. Make sure you have your dataset (e.g., customer_churn_data.csv) in the correct directory.
4. Run the script
   ```bash
   python churn_prediction.py
5.Check the output for model evaluation and predictions.


## Conclusion

This project demonstrates how a **Random Forest Classifier** can be used to predict customer churn based on demographic and account data. By identifying customers at risk of leaving, businesses can take proactive actions to retain valuable customers. 

Future enhancements could include:
- **Hyperparameter tuning** to optimize model performance.
- Exploring other machine learning models (e.g., Gradient Boosting, XGBoost) for better accuracy.
- Expanding the dataset to include more features and improve predictions.

This project provides a foundational approach to customer retention and predictive analytics using machine learning.

  
   

