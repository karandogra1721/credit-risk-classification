# credit-risk-classification

# Overview of the Analysis
The purpose of this analysis was to develop machine learning models to predict loan status based on financial information. The dataset contained various features related to loan applicants, such as credit score, annual income, debt-to-income ratio, and employment length. The target variable was the loan status, which had two classes: "0" representing healthy loans and "1" representing high-risk loans.

Initially, I performed exploratory data analysis to understand the distribution of loan statuses and the relationships between features and the target variable. I then split the data into training and testing sets, trained several machine learning models, and evaluated their performance using accuracy, precision, and recall scores.

# Results
## Logistic Regression Model:
Accuracy: 99%
Precision for class 0 (healthy loan): 100%
Precision for class 1 (high-risk loan): 84%
Recall for class 0 (healthy loan): 99%
Recall for class 1 (high-risk loan): 94%

# Summary
The logistic regression model performed exceptionally well in predicting both healthy and high-risk loans. It achieved near-perfect precision and recall for healthy loans, indicating that it accurately identified the vast majority of healthy loans and rarely misclassified them. While the precision for high-risk loans was slightly lower, the model demonstrated high recall, correctly identifying a significant portion of high-risk loans with fewer false negatives.

In this context, where the consequences of misclassifying high-risk loans could be severe, the logistic regression model's balance between precision and recall makes it a suitable choice. However, it's essential to consider the specific problem context and business objectives. If the priority is to minimize the risk of approving high-risk loans, a model with higher precision for class 1 might be preferred. Conversely, if the goal is to capture as many high-risk loans as possible, a model with higher recall for class 1 might be more appropriate.

Overall, based on its strong performance and balanced precision-recall trade-off, the logistic regression model is recommended for predicting loan statuses in this scenario.