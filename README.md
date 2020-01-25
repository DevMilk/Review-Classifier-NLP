# Review-Classifier-NLP
It is a Natural Language Processing work using 2 Machine Learning Algorithms and a Keras Deep Learning model

# Its aim is to classify a review as positive, negative or neutral

Lemmatizing, Cleaning, and vectorizing reviews are done by prepare function and nltk library functions

-----
Naive Bayes Classification got %62, Logistic Regression Algorithm got %79 test accuracy.

Neural Network reaches up to %87 test accuracy which is very nice. Adding layers don't change loss and without initializing first weights with lecun uniform model is limits itself by %80 accuracy. Model may be improved using BERT model and other initializer-regularizer combinations.

Kaggle: https://www.kaggle.com/uurdeep/predict-review-with-ml-and-dl-87-accuracy


Comparisons:

![alt text](https://github.com/DevMilk/Classifying-reviews/blob/master/__results___17_1.png)

Learning process:

![alt text](https://github.com/DevMilk/Classifying-reviews/blob/master/plot.png)
