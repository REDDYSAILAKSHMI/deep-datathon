# Deep Datathon
This project is about identifying the fake websites based on URLs.
### For preprocessing,the techniques used are
- CountVectorizer <br>
It is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.
- TfidVectorizer <br>
The process of transforming text into a numerical feature is called text vectorization. TF-IDF is one of the most popular text vectorizers, the calculation is very simple and easy to understand. It gives the rare term high weight and gives the common term low weight.
### Techniques used for Model Training 
- Logistic Regression() <br>
 Logistic regression is an example of supervised learning. It is used to calculate or predict the probability of a binary (yes/no) event occurring.
- MultinomialNB() <br>
 The Multinomial Naive Bayes algorithm is a Bayesian learning approach popular in Natural Language Processing (NLP). The program guesses the tag of a text, such as an email or a newspaper story, using the Bayes theorem. It calculates each tag's likelihood for a given sample and outputs the tag with the greatest chance.
- XGB Classifier <br>
 XGBoost, which stands for Extreme Gradient Boosting, is a scalable, distributed gradient-boosted decision tree (GBDT) machine learning library. It provides parallel tree boosting and is the leading machine learning library for regression, classification, and ranking problems.
 ## The results are as follows:
 - Logistic Regression() : 92<br>
 - MultinomialNB() : 93<br>
 - XGB Classifier : 88 <br>
 
