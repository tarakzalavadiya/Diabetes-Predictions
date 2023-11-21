# Nearest-Neighbors-Classification-using-KNN-Algorithm

- Conducted exploratory data analysis on a dataset of 768 rows and 9 features, addressing missing values through a combination of median imputation and KNN imputation for substantial data gaps.
  
- Employed feature selection methods (Pearson correlation and 'SelectKBest' with 'f_regression') to identify influential features, ultimately selecting Glucose, Age, BMI, Pregnancies, and Skin Thickness.

- Executed standard scaling for KNN algorithm compatibility, followed by an 80-20 train-test split and 10-fold cross-validation with a KNN classifier.

- Utilized the elbow method to identify the optimal K value (K=13) for the classifier, achieving an overall accuracy of 76% with a recall of 88% for class 0 and 54% for class 1.

- Plotted an AUC-ROC curve, attaining a value of 82%. Evaluated precision, recall, and F1-score, noting improvement with increasing K values.

- Observed an intriguing trend in precision and recall for class 1 as K increased, emphasizing the trade-off between precision and recall.

- Overall accuracy showed improvement from 73% (K=7) to 77% (K=16 and K=20). Error rate vs. K plot indicated a decreasing trend.

This project demonstrated adept handling of missing data, feature selection, scaling, and model evaluation, showcasing a nuanced understanding of KNN algorithm dynamics.
