# Emoji-Predictor-LSTM
Aim:- Our Motivation behind it was to make model which can predict the Emoji related to text using NLP techniques.
Data Preparation Part:-
  Train Data:- As a train data we were given the comments scraped over the net and those are labled with relevant emoji.
  Test Data:- The comments are given and we have to find the most relevant emoji.
Model Planning:-
  As we got the intution that it is many to one model. We have to Deploy a model which learn the structuring of comments so we have used
  the LSTM model(Long Short Term Memory), The great idea about LSTM is it's capability to learn and store the past data and learning the
  structure od sentences and making sence out of them. It consists of three gate $Forget Gate, $Input Gate, $Output Gate.
  Also we need to care about the input size, as if we use the count Vectorization Method then we'll be having very large dataset of
  rows of no of comments and coloums size of vocab size, so avoiding such a complex input layer we introduce a embedding layer.
