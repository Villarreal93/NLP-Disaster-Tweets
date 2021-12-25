# NLP Disaster Tweets
A LSTM is used to predict whether the tweets of the test data are disasters or not. In the column "Target", a value of 1 denotes a disaster while a 0 denotes the contrary. The data is preprocessed with tools like NLTK and trained/padded using tensorflow. The youtube video does not use the model to predict the test data, only the validation data. Thus, I have included a prediciton of the model with the tokenized/padded test data. Additionally, the LSTM is trained using keras tuner to reduce overfitting. Finding the units of the LSTM and the best learning rate for the Adam Optimizier, through this method, increased the model's accuracy by around 8%. 

# Reference
I saw this idea on Python's Engineer Youtube channel, and I'm only using it to learn. If interested, go watch his full video (& channel!) on how to do this project: https://youtu.be/kxeyoyrf2cM. 

The data is available on Kaggle, where you can also join the competition: https://www.kaggle.com/c/nlp-getting-started/overview
