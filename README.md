# Disaster-Tweet-Classification
Twitter has become an important communication channel in times of emergency. Twitter boasts 330 million monthly active users, which allows people to reach a broad audience and connect with others without intermediaries. Listening to users on Twitter allows organizations like disaster relief and government agencies to understand more about a disaster event, keep on top of what’s being said about the event, discover new updates and analyze people’s reactions to the event. But it is not always clear whether a person’s tweet is actually about a disaster for humans and especially for difficult machines. For example let's look at this tweet, “Damage to school bus on 80 in multi car crash #BREAKING”  from this tweet we can clearly understand that the person is tweeting about a disaster. Let's look at the following tweet “Had an awesome time visiting the CFC head office, the ancop site and ablaze. Thanks to Tita Vida for taking care of us ??” here the person is referring to the experience of visiting a company, we should not consider the literal meaning here. This kind of inference is difficult for machines. This project explores deep learning models that predict which Tweets are about real disasters and which ones are not.

# Dataset
Each sample in the train and test set has the following information:

1. The text of a tweet
2. A keyword from that tweet 
3. The location the tweet was sent from 


# Models used
1. Deep Neural Network model
2. Convolutional Neural Network model 
3. GloVe Vector Embeddings with LSTM model
4. BERT model

with BERT predicting highest accuracy of 96%
