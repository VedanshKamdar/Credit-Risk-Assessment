## *Credit Risk Assessment using Machine Learning models*

Credit risk analysis is essential for financial institutions to assess the probability of default among potential borrowers. This project employs logistic regression and various machine learning models on the American Express dataset to evaluate credit risk. The objective is to identify the most effective model for predicting credit card defaults and to determine the key variables influencing credit risk. Our analysis reveals that XGBoost outperforms other models, achieving an accuracy of 0.97, a precision of 0.91, an F1-score of 0.91, and an AUC value of 0.92. While logistic regression and other models also show strong performance, they do not match the efficacy of XGBoost. The study identifies credit score, credit limit utilization, and the number of days employed as the most critical factors in predicting credit card defaults, whereas the borrower's age is found to be insignificant. These findings underscore the importance of incorporating diverse variables in credit risk analysis. The study offers valuable insights for financial institutions to enhance their credit risk models using machine learning techniques like XGBoost, thereby improving their ability to identify and manage credit risk and minimizing losses from defaults.

## *Experimental result*

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.9464   |
| Random Forest       | 0.9650   |
| Decision Tree       | 0.9683   |
| KNN                 | 0.9681   |
| XGBoost             | 0.9693   |

| Model | Data | Accuracy | F1 Score | RMSE | ROC AUC |
|-------|------|----------|-----------|------|---------|
| Logistic Regression | Train | 95.74082 | 95.74031 | 0.20638 | 0.95741 |
| Logistic Regression | Test | 94.66667 | 86.00746 | 0.23094 | 0.95924 |
| Decision Tree | Train | 100.00000 | 100.00000 | 0.00000 | 1.00000 |
| Decision Tree | Test | 96.83333 | 90.18608 | 0.17795 | 0.93039 |
| Random Forest | Train | 100.00000 | 100.00000 | 0.00000 | 1.00000 |
| Random Forest | Test | 96.50000 | 89.50839 | 0.18708 | 0.93781 |
| XGBoost | Train | 99.42415 | 99.42414 | 0.07588 | 0.99424 |
| XGBoost | Test | 96.93333 | 90.63899 | 0.17512 | 0.94202 |
| KNN | Train | 99.36968 | 99.36966 | 0.07939 | 0.99370 |
| KNN | Test | 96.81111 | 90.04948 | 0.17858 | 0.92595 |
