# Heart-Disease-Prediction
This project aims to predict the presence or absence of heart disease in patients based on various health parameters. The model uses machine learning algorithms to classify individuals as either having heart disease (Presence) or not (Absence). The project includes data preprocessing, model training, evaluation, and fine-tuning using ensemble methods.
## Steps Involved
1. **Data Preprocessing**:
   - Handle missing values and encode categorical variables.
   - Normalize and standardize numerical features.
   - Split the dataset into training and testing sets.
   
2. **Model Training**:
   - Train multiple models (Random Forest, Gradient Boosting, Logistic Regression).
   - Tune hyperparameters using GridSearchCV for optimal results.
   
3. **Ensemble Method**:
   - Combine the models into a Voting Classifier (hard or soft voting).
   
4. **Evaluation**:
   - Evaluate models using accuracy, precision, recall, F1-score, and AUC.
   - Compare results from different models and fine-tune for better performance.
