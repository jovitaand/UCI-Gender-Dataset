# Income Prediction Using Machine Learning Models

This project aims to build and evaluate machine learning models that predict whether an individual earns more than $50,000 per year based on demographic and work-related features. The dataset used for this project comes from the UCI Adult dataset, which includes features such as age, education, occupation, race, gender, and more.

### Models Used:
- **Logistic Regression**
- **Random Forest**
- **Gradient Boosting**

### Key Objectives:
- **Data Cleaning and Preprocessing**: Handle missing values and perform one-hot encoding for categorical variables.
- **Model Training and Evaluation**: Train multiple machine learning models and evaluate their performance using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.
- **Fairness Assessment**: Analyze model performance across protected groups (e.g., race and gender) to ensure fairness and mitigate bias.
- **Visualization**: Generate confusion matrices and ROC curves to interpret the model's effectiveness.

### Responsible AI Considerations:
This project also explores the ethical implications of using machine learning to predict income, focusing on potential biases in the model that could negatively affect individuals and marginalized communities.

### Conclusion:
After evaluation, **Gradient Boosting** was selected as the best-performing model, balancing high accuracy and fairness across protected groups. However, the project emphasizes the need for further fairness checks before deploying such models in real-world applications to avoid perpetuating systemic inequalities.
