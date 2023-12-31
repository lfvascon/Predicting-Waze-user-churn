# Predicting-Waze-user-churn.

## Project Overview
Is a machine learning project aimed at predicting user churn within the Waze application. The project involves building and evaluating classification models, specifically decision tree, random forest, and XGBoost, to identify patterns and factors influencing user churn. By understanding user behavior and engagement metrics, Waze can proactively take measures to retain users and enhance their overall experience.

## Business Understanding
Waze relies heavily on user engagement and satisfaction to maintain its competitive edge. Understanding and predicting user churn is crucial for optimizing user retention strategies. By identifying potential churners in advance, Waze can implement targeted interventions such as personalized notifications, feature enhancements, or promotional offers to encourage users to remain active on the platform.

## Data Understanding
The data team will delve into Waze's extensive dataset, encompassing user interactions, navigation history, feature usage, and other relevant metrics. Exploratory data analysis (EDA) will be conducted to uncover patterns, correlations, and anomalies. This phase will inform feature selection and preprocessing strategies for the subsequent modeling phase.

## Modeling and Evaluation
The team will implement three classification models: decision tree, random forest, and XGBoost. These models will be trained on historical data, utilizing features identified during the data understanding phase. The models will be fine-tuned to achieve optimal performance. Evaluation metrics will include accuracy, precision, recall, and F1-score. The team will focus on achieving a balance between correctly identifying potential churners and minimizing false positives. Cross-validation techniques will be employed to ensure robustness and generalizability of the models.

## Conclusion
The ML models demonstrate a critical need for additional data in order to more accurately predict user churn. This modeling effort confirms that the current data is insufficient to consistently predict churn. It would be helpful to have drive-level information for each user (such as drive times, geographic locations, etc.). It would probably also be helpful to have more granular data to know how users interact with the app. For example, how often do they report or confirm road hazard alerts? Finally, it could be helpful to know the monthly count of unique starting and ending locations each driver inputs.
