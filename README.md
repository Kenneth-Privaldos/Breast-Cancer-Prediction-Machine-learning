# Breast Cancer Prediction using XGBoost
# Introduction
Breast cancer ranks as one of the leading cancer types affecting women globally. Timely and accurate diagnosis is crucial, as early detection is pivotal for effective treatment outcomes. This project aims to harness the power of machine learning to develop a predictive model that can distinguish between benign and malignant breast cancer tumors. Utilizing a dataset enriched with features such as tumor size, shape, and texture, we will employ the XGBoost algorithm—a renowned and potent machine learning technique known for its performance in classification tasks.

XGBoost, short for eXtreme Gradient Boosting, is celebrated for its efficiency and scalability. It operates on the principle of gradient boosting, optimizing both speed and accuracy to handle large-scale and complex data. By leveraging XGBoost, our model will not only provide precise predictions but also offer insights into the importance of each feature, contributing to a deeper understanding of the factors influencing breast cancer malignancy.

The outcome of this project will be a robust tool that healthcare professionals can utilize to improve diagnostic accuracy, ultimately aiding in the fight against breast cancer by enabling earlier interventions.

# Data
The dataset we will use for this project is the Wisconsin Breast Cancer dataset, which is available in the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29). The dataset contains a total of 569 instances, with 357 benign and 212 malignant tumors. Each instance has 30 features, which represent various characteristics of the cell nuclei present in the digital image of the fine needle aspirate (FNA) of the breast mass.

# Preprocessing
Before we can train our model, we will need to preprocess the data to handle missing values and convert non-numeric features into numeric ones. We will also split the dataset into training and testing sets to evaluate the performance of our model.

# Training
Next, we will train our XGBoost model on the training data. We also trained the data using SVM to compare the performance. 
# Evaluation
After training the model, we will evaluate its performance on the testing data. We will use various metrics such as precision, recall, and F1 score to assess the quality of the model's predictions. We will also use cross validation and Stratified KFold to evalute the model and calculate the Average accuracy.

# Conclusion
In this project, we built a machine learning model to predict whether a breast cancer tumor is benign or malignant using the XGBoost algorithm. We preprocessed the data, trained the model, and evaluated its performance on the testing data. With the appropriate parameters and evaluation metrics, we were able to achieve good results and improve the chances of successful treatment for breast cancer patients.
