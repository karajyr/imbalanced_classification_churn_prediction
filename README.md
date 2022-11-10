# imbalanced_classification_churn_prediction
The purpose of this project is to: (1) develop algorithms to identify customers who are likely to churn in the future (2) analyze top factors that influence user retention (3) interpret results and give business suggestions accordingly.

Key take aways:

- Mitigate impact of imbalanced data on classification by methods such as stratified sampling and **SMOTE**, which improved ~50% of model performance.
- Select **recall** as the most suitable metric for this particular project, achieving best recall of 69.74% by XGBoost
- 5 Most important factors:   
    - **Age**: older customer are more likely to churn;  
    -  **NumOfProducts**: churn customer tend to use more products;  
    - **Gender**: female are more likely to churn;   
    - **Geography**: Customer from Germany are more likely to churn;  
    - **IsActiveMember**: Non-active members are more likely to churn.  
- Business Suggestions: See Part 6
