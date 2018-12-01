# Sentence-Classification
Using 1-Dimensional CNN to classify movie reviews

### 1-Dimensional Convolutions

When we hear about Convolutional Neural Network (CNNs), we typically think of Computer Vision. CNNs were responsible for major breakthroughs in Image Classification and are the core of most Computer Vision systems today, from Facebook’s automated photo tagging to self-driving cars.

More recently we’ve also started to apply CNNs to problems in Natural Language Processing and gotten some interesting results.

Instead of image pixels, the input to most NLP tasks are sentences or documents represented as a matrix. Each row of the matrix corresponds to one token, typically a word, but it could be a character. That is, each row is vector that represents a word. Typically, these vectors are word embeddings (low-dimensional representations) like word2vec or GloVe, but they could also be one-hot vectors that index the word into a vocabulary. For a 10 word sentence using a 100-dimensional embedding we would have a 10×100 matrix as our input. That’s our “image”.

[WildMl CNN for NLP tutorial](http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/)

The model arhitecture is briefly described :

![alt text](https://github.com/ritam006/Sentence-Classification/blob/master/cnn_multichannel_glove.png)
