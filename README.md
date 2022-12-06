# imbalanced_classification_churn_prediction
  This goal of this project is to handle the imbalanced classification problem by developing algorithms to identify customers who are likely to churn in the future, interpret results, and give business suggestions.

Methods used: 
- Handling imbalanced classfication problem by stratified sampling and **SMOTE**, which improved ~46% of model performance.
- Chose **recall** as the most suitable metric our business case, achieving best recall of 69.74% by XGBoost

5 most important factors:   
- **Age**: older customer are more likely to churn, especially those who are non-active; opposite is true for younger active customers 
-  **NumOfProducts**: customer who used more more than 3 products are more likely to churn; customers who only used 2 products with high account balance are especially likely to churn  
- **Gender**: females are more likely to churn. This is driven by non-German females are more likely to churn compared to German females.  
- **Geography**: Customer from Germany are more likely to churn, especially those who tried more products;  
- **IsActiveMember**: Non active members are more likely to churn; but younger active members are more likely to churn  
  
Business suggestions: See Part 6
    
