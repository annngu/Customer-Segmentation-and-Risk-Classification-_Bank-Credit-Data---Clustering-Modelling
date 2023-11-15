# Customer-Segmentation-and-Risk-Classification-_Bank-Credit-Data---Clustering-Modelling

#Bivariate and Univariate Analysis:

The project starts with exploratory data analysis, which includes both bivariate and univariate methodologies. This entails investigating correlations between variables and evaluating individual variables in order to discover patterns and trends in the data.

#Data Cleaning:
Cleaning the dataset to deal with missing values, outliers, and inconsistencies is an important step. This ensures that the dataset is of excellent quality for further studies and model training.



#Preprocessing Data & Data Sampling:
The data is preprocessed to make it suitable for machine learning techniques. Normalization, scaling, and encoding categorical variables are among the techniques used. Furthermore, data sampling strategies can be used to balance class distributions, particularly in the case of imbalanced datasets.


#Unsupervised and Supervised Machine Learning:
Unsupervised learning techniques, such as clustering, are implemented for customer segmentation. This helps identify distinct groups within the customer base. On the other hand, supervised learning models, including XGBoost, are employed for risk classification, predicting whether a customer is likely to be a credit risk.

#Customer Segmentation:The initiative intends to segment clients based on their financial behavior or other relevant attributes using unsupervised learning. This segmentation can help with targeted marketing and personalized services.


#Optimizing Hyperparameters: To improve the performance of machine learning models, hyperparameter tuning is used. RandomizedSearchCV techniques are used to efficiently search the hyperparameter space and discover the optimal combination for the XGBoost classifier.



#Risk Classification with Predictive Modeling using XGBoost:
XGBoost, a powerful gradient boosting algorithm, is employed for risk classification. The model is trained on historical data to predict whether a customer is likely to default on a credit. This predictive modeling aids in making informed decisions about credit approvals.

#ROC Analysis:


The risk categorization model's performance is evaluated using Receiver Operating Characteristic (ROC) analysis. To measure the model's discriminatory abilities, plot the true positive rate against the false positive rate at various thresholds and calculate the Area Under the Curve (AUC).

In Conslusion , this study demonstrates a comprehensive method to credit risk assessment that combines exploratory data analysis, machine learning, and advanced analytics to deliver actionable insights for financial decision-making. Customer segmentation and proper credit risk classification assist to more successful and informed company strategy.




