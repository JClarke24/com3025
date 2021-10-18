# README.md

The goal of this project is aimed at creating a sentiment analysis model, which is used to predict the sentiment of the text (positive, negative or neutral). The model would take an input of selected text and the sentiment associated with that text and then train the model based on this data.
One of the implementations chosen was to use an LSTM model. Given that the text in the tweets is sequential data, I thought that using an LSTM to model these would be a good idea seeing as LSTMs have the ability to “remember” and “forget” information it has seen. Also, as we are dealing with a large number of tweets, having a model that can learn long-term dependencies may prove useful. This approach allows the model to understand the context of a specific word.
