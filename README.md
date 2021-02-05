# Emoji-Prediction-

The goal of our project is to predict an emoji for a given sentence.
The reason we chose this topic is to minimise the effort taken to look for an emoji while typing a sentence. 


We created our own dataset for this project.
Our dataset contains text data, i.e: it consists of simple sentences and a numerical value for each sentence in the data. 
These values are labels assigned to each sentence from 0 to 4. 
We’ve chosen just 5 emojis for our project and hence the labels 0 to 4.

METHODOLOGY
We used recurrent neural networks.
Recurrent Neural Network(RNN) are a type of Neural Network where the output from previous step are fed as input to the current step. 
In traditional neural networks, all the inputs and outputs are independent of each other, but in cases like when it is required to predict the next word of a sentence, the previous words are required and hence there is a need to remember the previous words. Thus RNN came into existence. 
And since our data is text data we used glove vectors to represent each word as a vector. 

