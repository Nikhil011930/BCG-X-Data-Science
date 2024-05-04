**Predictive Model Building Task - README**

**Introduction:**
This repository contains the code and dataset for building a predictive model using a CSV file shared by Estelle. The task involves training a predictive model to identify churn based on a set of cleaned and engineered features.

**Setup:**
To begin, download both the Jupyter notebook and CSV file provided in this repository. Run the cells within the notebook to load the data and create train and test samples.

**Data Splitting:**
- **Train and Test Samples:** It's crucial to split the data into train and test samples to measure the model's performance on unseen data. This ensures a reliable assessment of the model's predictive capabilities.

**Model Building:**
- **Random Forest Classifier:** The notebook provides skeleton code for creating a random forest classifier. Your task is to fill in the details of the code using the documentation provided.
- **Parameter Tuning:** Adjust parameters within the random forest to optimize model performance.
- **Model Training:** Fit the model on the training data to obtain a trained model capable of predicting churn.

**Model Evaluation:**
- **Metric Selection:** Evaluation of the model's performance is left to your discretion. In the notebook, three metrics—accuracy, precision, and recall—are used.
- **Understanding Metrics:** The choice of metrics reflects the need for a comprehensive assessment of model performance. Accuracy alone may not adequately capture the implications of false positives and false negatives, particularly in critical scenarios such as predicting medical conditions.
- **Interpreting Results:** Analysis of the metrics reveals insights into the model's strengths and weaknesses. While the model accurately identifies clients who do not churn, it struggles to predict clients who will churn. This suggests that the current set of features may not effectively predict churn, prompting the need for feature engineering.

**Feature Importance Analysis:**
- **Visualization:** A feature importance chart is generated to visualize which features were most useful within the model.
- **Insights:** Net margin and consumption over 12 months emerge as important features. However, price sensitivity features show scattered importance and do not strongly influence churn prediction in their current form.

**Conclusion:**
This predictive modeling task provides valuable insights into churn prediction using a random forest classifier. By evaluating model performance, understanding the implications of metrics, and analyzing feature importance, we gain a deeper understanding of the dataset and avenues for improving churn prediction accuracy through feature engineering.