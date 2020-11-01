Our project is about recognizing the spam message since there are a lot of spam messages in our life. The purpose of this project is to recognize the spam message with high accuracy. We created the three models which are Logistic Regression, Bernoulli Naive Bayes Classifier, and LSTM(Long short-term memory) which is a deep learning model. We provide the code for the three models and data visualization as well as the best model for deep learning model. The explanation for files is following.

logistic_regression.ipynb
※ Code for logistic regression model
※ If you implement the code after "Using the cross-validation", you have to change your _validaion.py (sklearn/model_selection/_validaion.py) to _validation.py we provided.

bernoulli_naive_bayes_classifier.ipynb
※ Code for bernoulli naive bayes classifier
※ If you implement the code after "Using the cross-validation", you have to change your _validaion.py (sklearn/model_selection/_validaion.py) to _validation.py we provided.

deep_learning_model.ipynb
※ Code for the deep learning model (LSTM)

model.h5
※ The best model for the deep learning model (LSTM)

data_visualization.ipynb
※ Code for data visualization of our dataset
※ In this file, there are some codes for data visualization like word cloud.

sms_spam.csv
※ The dataset we used

_validation.py
※ This is one of the files in scikit-learn. We changed scikit-learn for our project.