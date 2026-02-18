# Bankruptcy Prediction in Poland

In this project, we construct a **Random Forest classifier** to predict the bankruptcy of companies in Poland. The project was inspired by a course I attended at **WorldQuant University**, during the **Applied Data Science Lab**.

The dataset used for this project is publicly available and can be downloaded from [Kaggle](https://www.kaggle.com/datasets/stealthtechnologies/predict-bankruptcy-in-poland).

The goal of this project is to demonstrate practical skills in:

- Data preprocessing: handling missing values with median imputation and missing indicators
- Feature engineering: creation of informative indicators such as `A27_missing`
- Model training: Random Forest classifier with proper train/test split and oversampling
- Model evaluation: using metrics suitable for imbalanced data, including **ROC-AUC, PR-AUC, precision, recall, F1-score, and confusion matrix**
- Feature interpretation: understanding the contribution of features such as `year` and artificially added indicators

The notebook includes detailed comments, explanations of the methodology, and visualization of results. Check the notebook for more information regarding the preprocessing steps, model training, and evaluation results.


