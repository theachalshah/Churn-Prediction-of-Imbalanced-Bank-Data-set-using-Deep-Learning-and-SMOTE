# Churn-Prediction-of-Imbalanced-Bank-Data-set-using-Deep-Learning-and-SMOTE

Customer churn is a critical metric because it is much more cost effective to retain existing customers than it is to acquire new customers as it saves cost of sales and marketing.

Artificial Neural Network has started playing a crucial role to predict churn but it itself is not enough because the dataset is not clean and imbalanced in the form of majority and minority class. Initially, null values have to be dealt with if any and then categorical values and unique values have to be converted in the form of 1 or 0 if any using One Hot Encoding.

If there is imbalanced data as in this case, the model will not be efficient especially with minority class. There are various ways to deal with it. Here SMOTE(Synthetic Minority Oversampling Technique) is used. It generates synthetic over samples of minority class using K nearest neighbor algorithm. Thus, improves overall efficiency.

Repository link - https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

Model – ANN with dropout regularization

