# diabetes_PIMA_project

The objective of this project was to develop a predictive model to determine the likelihood of diabetes onset using diagnostic measures from the PIMA Indians Diabetes Database. By implementing and comparing Logistic Regression and Random Forest classifiers, we aimed to identify the most accurate model and the key diagnostic factors influencing diabetes.

Our data preprocessing steps, including handling missing values and standardizing features, ensured that the dataset was clean and suitable for modeling. Exploratory Data Analysis (EDA) provided valuable insights into the distributions and relationships between features, guiding our modeling efforts.

Both Logistic Regression and Random Forest models were trained and evaluated using a train-test split approach. Hyperparameter tuning through GridSearchCV optimized the performance of the Random Forest classifier, while Logistic Regression served as a baseline model. Model performance was rigorously assessed using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

The Random Forest classifier emerged as the more robust model, achieving higher accuracy and better overall performance. Feature importance analysis revealed that certain diagnostic measures, such as glucose levels and BMI, had a significant impact on the likelihood of diabetes onset.

In conclusion, this project successfully demonstrated the application of machine learning techniques to predict diabetes. The Random Forest model, with its superior performance and interpretability, provided valuable insights into the key factors influencing diabetes. These findings can aid healthcare professionals in early diagnosis and intervention strategies, ultimately contributing to better patient outcomes. The project highlights the importance of data preprocessing, model selection, and rigorous evaluation in developing effective predictive models
