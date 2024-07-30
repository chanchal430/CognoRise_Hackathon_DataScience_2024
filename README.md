# CognoRise_Hackathon_DataScience_2024
## Project Overview
- This project was developed using an MLOps approach, ensuring a systematic and efficient workflow for data analysis, preprocessing, model selection, and training. The aim was to predict high school students' exam scores based on various demographic and performance-related features.

## Workflow
- **Data Analysis:** Conducted an exploratory data analysis to understand the distribution and relationships within the dataset.
- **Data Preprocessing:** Cleaned the data, handled missing values, and performed feature engineering to enhance the predictive power.
- **Model Selection:** Evaluated multiple machine learning models to identify the best-performing one.
- **Model Training:** Trained the selected model using the filtered data.
## Selected GradientBoost for This project

## Justification:
- After evaluating several models, the GradientBoost Regressor was chosen for the following reasons:

- **High Performance:** Demonstrated the best balance between bias and variance, achieving strong performance on the validation set.
- **Robustness:** Less sensitive to outliers and capable of capturing complex interactions within the data.
- **Feature Importance:** Provided clear insights into the importance of various features, aiding in model interpretability.

### Handling Overfitting:
- Applied cross-validation and fine-tuned hyperparameters to ensure the model generalized well to unseen data.

- **Key Findings**
- Feature Insights: Practical scores and viva scores were identified as the most significant predictors of exam scores.
- Model Performance: GradientBoost achieved the highest R² score, indicating a strong predictive capability.
  
## Conclusion
The GradientBoost Regressor was selected as the final model due to its superior performance and robustness. 
