# Sub-task A
Offensive language identification

## ML

We have used various Machine Learning techniques (like Logistic Regression , Linear SVC , LinearSVC with L1-based feature selection ,Multinomial NB , Bernoulli NB etc.) to classify the tweets.
We have validated our models using 15 percent of the training data.
We have conducted several experiments and have found the best validation accuracy for :
    1. Countvectorizer
    2. Tri-gram
    3. 90,000 features

Now among the various classifiers, we have built an ensemble (voting) classifier with top 5 models and found the best accuracy result for :
    Logistic Regression

So, Key-points of our Model is :
    1. Countvectorizer
    2. Tri-gram
    3. 90,000 features
    4. Logistic Regression

## CNN

In this submission we have used Convolutional Neural Network to classify the tweets.
We have used Glove(300 dimension) for pre-trained embedding.
We have parsed the cleaned tweets to generate vector sequence for traing through embedding layer.

Here is the model summery :

<img src="graph_run.png?raw=true">