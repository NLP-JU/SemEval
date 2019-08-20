# Sub-task B
Automatic categorization of offense types

## ML

We have used various Machine Learning techniques to classify the tweets.
We have validated our models using 15 percent of the training data.
We have conducted several experiments and have found the best validation accuracy for :
    1. Countvectorizer
    2. Tri-gram
    3. 50,000 features
Now among the various classifiers, we have built an ensemble (voting) classifier with top 5 models and found the best accuracy result for :
    Logistic Regression

So, Key-points of our Model is :
    1. Countvectorizer
    2. Tri-gram
    3. 50,000 features
    4. Logistic Regression

## RNN

We have used LSTM - RNN network for tweet classification.
Hyperparameters :
    1. batchsize = 24
    2. lstm units = 64
    3. epochs number = 1,00,000
We have used Glove embeddings of 200D vectors.
We have used 2 class layer for training.
We have found that model gives better validation accuracy while fitted with cleaned data parsing with @user.
While training the RNN- Lstm network we have used alternative Targeted and Non -targeted tweets from annotated data.
We have used : 
    1.ADAM optimizer.
    2.Accuracy as Metric.
    3.Cross entropy.

Here is the model summery :

<img src="model_rnn.png?raw=true">