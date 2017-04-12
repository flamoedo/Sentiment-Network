# Sentiment-Network
Sentiment analysis with TFLearn - LSTM

In this notebook, I adapt the Andrew Trask's work, and Siraj Sentimental Network, 
by building a network for sentiment analysis on the movie review data. 
The main diference is that instead of use "imdb.pkl" that is already processed word's vectors, I've used the original sentences 
in reviews and labels, so in the end of the day, you can use the network with real word reviews collected from IMDB site, and make 
predictions, with high accuracy.
I've used TFLearn, a high-level library built on top of TensorFlow. TFLearn makes it simpler to build networks just 
by defining the layers. It takes care of most of the details for you. We'll start off by importing all 
the modules we'll need, then load and prepare the data.

Activate a python3 conda environment. In this environment, you'll need to have installed 
jupyter notebook, matplotlib, pandas, numpy, tensorflow and tflearn

Download the following files, with labels and reviews

labels: https://github.com/udacity/deep-learning/blob/master/sentiment-network/labels.txt

reviews: https://github.com/udacity/deep-learning/blob/master/sentiment-network/reviews.txt
