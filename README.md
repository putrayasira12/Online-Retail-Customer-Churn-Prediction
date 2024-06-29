**Online Retail Customer Churn Prediction**

### Project Overview 📊
This project aims to create a classification model to predict whether a customer will churn or not. The model will use features likely to affect the customer's decision to churn. Five algorithms will be evaluated: K-Nearest Neighbors, Support Vector Machine, Decision Tree, Random Forest, and AdaBoost. These models will be tuned to identify the best one for classification. Recall will be used as the primary metric to evaluate the model's ability to identify customers who will churn and minimize undetected churn.

### Objective 🎯
Create a classification model to predict customer churn using features influencing churn decisions. The model will evaluate five algorithms: K-Nearest Neighbors, Support Vector Machine, Decision Tree, Random Forest, and AdaBoost. The models will be tuned and evaluated using recall to ensure accurate churn prediction and minimize undetected churn cases.

### Results 📈

**Data Analysis:**
- Total customer data: 1000
- Churn Target: Classifies customers who will churn or not.
- Average Total Spend is very small compared to Annual Income.
- Numeric data distribution: Normal
- Gender distribution: 34% Female, 33% Male, 32% Other
- Annual income range: $179k
- Customer loyalty range: 1 to 19 years
- 90% of customers have returned goods.
- 32% of customers contacted Support more than once before resolving their issues.
- 18% of customers rated retail as excellent.
- 47% of customers did not provide their email.
- Only 34% of customers respond to promotions, with 36% opting to unsubscribe.

**Model Building:**
- Five models evaluated: K-Nearest Neighbors, Support Vector Machine, Decision Tree, Random Forest, and AdaBoost.
- Model evaluation metric: Recall
- Models tested using cross-validation to identify the best model for general data classification.
- Base model evaluation: Support Vector Machine was best judged by cross-validation.
- After tuning, the top models were SVM (1.00), Random Forest (0.92), and AdaBoost (0.90).
- Re-analysis showed AdaBoost as the most flexible model for the data, leading to its selection for the project.
- AdaBoost model successfully classified new data as True (customer will churn).

**Model Limitations:**
- The model tends to classify data as True even if it is incorrect, likely due to similar characteristics in each classification.

### Future Improvement 🚀
- Explore other algorithms to improve recall and accuracy.
- Continuous tuning and evaluation of models to adapt to new data.

### Conclusion 🏆
The AdaBoost model, after tuning, emerged as the best model, effectively classifying customer churn with a recall value of 90%. This high recall value ensures fewer false negatives, meaning fewer customers who should churn are missed by the model.

### Business Insights 💼

1. **High Return Rate (90%)**: Retail needs to improve Quality Control of goods before delivery to customers.
2. **Customer Support Efficiency**: 32% of problems require multiple contacts to resolve. Improve problem-solving efficiency through retraining or additional training for the support team.
3. **Customer Satisfaction**: Only 18% of customers rate retail as excellent. Conduct customer surveys to identify and address service shortcomings.
4. **Promotion Effectiveness**: 36% of customers unsubscribe from promotions. Evaluate and improve marketing strategies to make promotions more appealing and less annoying to customers.
5. **Email Collection**: Increase efforts to collect customer emails to broaden the reach of promotional activities.

By addressing these insights, the retail business can improve customer satisfaction, reduce churn, and enhance overall service quality.
