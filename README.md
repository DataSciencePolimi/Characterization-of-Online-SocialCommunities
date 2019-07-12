# Characterization-of-Online-SocialCommunities

This software allows to extract textual features vectors from texts in order to evaluate the characterization of Online Social Communities.

## Requirements

- Python > 3.0 for the extraction of NLTK and Dandelion features
- Python 2.7 for the extraction of Topic features
- nltk 3.2.5
- gensim 3.7.1
- DANDELION key


## Use the code

Clone the repository:

`git clone https://github.com/DataSciencePolimi/-Characterization-of-Online-SocialCommunities`


## Some useful notes

In the TopicFeatures notebook there are
- function to perform topic analysis in order to choose the correct number of topic
- function to create feature vector from the LDA model

In the feature_DANDELION notebook, using Dandelion the topic and instances features can be extracted and used to create semantic feature vectors.

In the feature_NLTK notebook, using NLTK the verb, noun and NNP features can be extracted and used to create syntactitc feature vectors.
