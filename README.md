### Task1
Data Preprocessing: The dataset was cleaned by dropping irrelevant columns and filling missing values (e.g., median for 'Age', mode for 'Embarked'). Categorical variables ('Sex' and 'Embarked') were converted to numerical values using label encoding.
Feature and Target Split: 'Survived' is treated as the target variable, while the rest are features.
Model Training: A Random Forest Classifier was used for training.
Model Performance: The model achieved an accuracy of ~82%, indicating a good fit for this classic Titanic survival prediction problem but leaving room for improvement with further feature engineering or hyperparameter tuning.
