Credit Card Default Prediction Using Machine Learning

Technologies: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook
- Developed a machine learning project to predict whether a customer is likely to default on credit card payments.
- Performed data cleaning, preprocessing, and exploratory data analysis (EDA) to understand customer payment behaviour.
- Handled missing values, duplicate records, and outliers to improve data quality.
- Applied categorical encoding and feature scaling as part of data preprocessing.
- Used data visualization techniques, including boxplots, count plots, and correlation heatmaps, to identify patterns and relationships.
- Split the dataset into training and testing sets to evaluate model performance.
- Implemented and compared three machine learning algorithms: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.
- Evaluated model performance using accuracy, precision, recall, and F1-score.

## Model Performance and Evaluation Results

The three machine learning classification algorithms were evaluated using Accuracy, Precision, Recall, and F1-score.

| Machine Learning Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.78 | 0.62 | 0.02 | 0.03 |
| Decision Tree Classifier | 0.73 | 0.39 | 0.41 | 0.40 |
| Random Forest Classifier | **0.82** | **0.64** | 0.36 | **0.46** |

### Performance Comparison

- **Logistic Regression:** Achieved 78% accuracy but had very low recall and F1-score.
- **Decision Tree Classifier:** Achieved 73% accuracy with a recall of 0.41 and an F1-score of 0.40.
- **Random Forest Classifier:** Achieved the highest accuracy (82%), precision (0.64), and F1-score (0.46) among the three models.

### Conclusion

Based on the evaluation results, the Random Forest Classifier performed best overall compared with Logistic Regression and Decision Tree Classifier. It achieved the highest accuracy and F1-score, making it the strongest-performing model in this project.

However, its recall of 0.36 indicates that it still misses a substantial proportion of actual credit card defaults. Further tuning and class-imbalance handling could improve its ability to identify customers who are likely to default.
