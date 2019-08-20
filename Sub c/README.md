# Sub-task C
Offense target identification

## RNN

We have used LSTM - RNN network for tweet classification.
Hyperparameters :
    1> batchsize = 24
    2> lstm units = 64
    3> epochs number = 40,000
We have used Glove embeddings of 200D vectors.
We have used 2 class layer for training.
We have found that model gives better validation accuracy while fitted with cleaned data parsing with @user.
While training the RNN- Lstm network we have used alternative Targeted and Non -targeted tweets from annotated data.
We have used : 
    1>ADAM optimizer.
    2>Accuracy as Metric.
    3>Cross entropy.

Here is the model summery :

<img src="rnn_c.png?raw=true">

## NN

In this submission we have used basic Neural Network to classify the tweets.

We have parsed the cleaned tweets to generate vector sequence for traing through embedding layer.

Here is the model summery :

<img src="nn_c.png?raw=true">