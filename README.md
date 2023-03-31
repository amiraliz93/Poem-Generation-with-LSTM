# Poem-Generation-with-LSTM

today text generating is a popular applications of **NLP** which use in vaeity tasks such as writing poemtry, script for videos and etc. In this code I will generate text by using DL models in Python using Keras

In this repository I aim to generate a poem in the style of William Blake by using Deep learning technique. I will use raw text from this poet to predict next word and generate poetry. 

# Road Map

1- First step is to download raw Data 
2- Second step is to prepare data for analysing ths stage include, removing punctuals, number, space, and etc
3- (Tokenisation), then we need to convert text to Number to be ready for train
4- creat input sequence for our DL model to train and predict the next word base on pervious sequence words
In pervious step we convert to sequence then we reshape to be 3-dimensional( LSTM model requre this shape) and then normalise 
5- Train model with Different model such as RNNs, LSTM, and GRU.
6- Predict and generate text 
7- the last step is to evalute model by BLUE Score

# Notice
you can find the colab code here https://colab.research.google.com/drive/1TAMXgpAegTfl7mrmgPdVEpMkl4jzoiRc?usp=sharing
