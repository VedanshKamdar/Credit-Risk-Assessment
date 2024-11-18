## *Credit Risk Assessment using Machine Learning models*

Credit risk analysis is essential for financial institutions to assess the probability of default among potential borrowers. This project employs logistic regression and various machine learning models on the American Express dataset to evaluate credit risk. The objective is to identify the most effective model for predicting credit card defaults and to determine the key variables influencing credit risk. Our analysis reveals that XGBoost outperforms other models, achieving an accuracy of 0.97, a precision of 0.91, an F1-score of 0.91, and an AUC value of 0.92. While logistic regression and other models also show strong performance, they do not match the efficacy of XGBoost. The study identifies credit score, credit limit utilization, and the number of days employed as the most critical factors in predicting credit card defaults, whereas the borrower's age is found to be insignificant. These findings underscore the importance of incorporating diverse variables in credit risk analysis. The study offers valuable insights for financial institutions to enhance their credit risk models using machine learning techniques like XGBoost, thereby improving their ability to identify and manage credit risk and minimizing losses from defaults.

## Experimental result

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 0.9464   |
| Random Forest       | 0.9650   |
| Decision Tree       | 0.9683   |
| KNN                 | 0.9681   |
| XGBoost             | 0.9693   |
