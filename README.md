# Blood-Donation-Forecast
This  project aims to predict future blood donations, addressing a critical issue in the healthcare system. The project utilizes machine learning techniques, specifically TPOTClassifier and logistic regression, to predict whether an individual will donate blood based on various factors such as income, schools, hospitals, and crime rates.

The project workflow includes the following steps:

1. **Data Preparation**: The dataset is read and preprocessed to prepare it for training the machine learning models. This includes renaming the target column for brevity and splitting the dataset into training and testing sets.

2. **Model Training**: Two models are trained on the training data: TPOTClassifier and logistic regression. TPOTClassifier is an automated machine learning tool that searches for the best machine learning pipeline for the classification task, while logistic regression serves as a baseline model.

3. **Model Evaluation**: The models are evaluated using the Area Under the ROC Curve (AUC) score, which measures the models' ability to distinguish between positive and negative classes. The AUC score helps assess the performance of the models in predicting blood donation behavior.

4. **Conclusion**: The project concludes that predicting future blood donations is a critical issue in the healthcare system. By utilizing machine learning models, the project demonstrates the potential to forecast blood donation behavior based on various factors. These predictions can aid healthcare organizations in better planning and managing blood donation campaigns, ensuring an adequate and timely supply of blood for patients in need.

5. **Future Work**: The project suggests further research and refinement of the models to improve prediction accuracy and healthcare outcomes.
