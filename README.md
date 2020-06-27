# Twitter Sentiment Analysis using Python Flask
## Installation :(twitter.nltk,re,csv,time and json)


- Tweepy: tweepy is the python client for the official Twitter API.
Install it using following pip command:

    `pip install tweepy`

- TextBlob: textblob is the python library for processing textual data.
Install it using following pip command:

    `pip install textblob`
    
- Install some NLTK corpora using following command:

    `python -m textblob.download_corpora`
    
(Corpora is nothing but a large and structured set of texts.)
## data set splitting 
- Creating a Supervised Machine Learning model is all about making a program that is able to generalize to input samples that it has never seen before. This task requires exposing the model — during training — to a certain number of variations of input examples, which is likely to lead to sufficient accuracy. This includes multiple steps that the model has to go through before it is available for use
##  getting the Authentication credentials:
        consumer_key = 'gGmTODeYtPsEAvPS9oh1oPIg8'
		consumer_secret = 'BZNQtcTqOBaTJ0RSdxac4Pf3SgHSdGJWflDGdpycRNr1spCoxi'
		access_token = '1205367961118113793-vikRw9XQ85JrIyWmmJ6ersI0ZNGdsY'
		access_token_secret = 'GSooDXnL01EwMi8aAHGCgV00UwMCZsbfL0ZbB5FeIqRP5'
## preparing thr Training set
    - Create function to download tweets based on a search keyword.
Registering an application with Twitter is critical, as it is the only way to get authentication credentials. As soon as we get our credentials, we will start writing code. Is where the Test set lies. We will be downloading tweets based on the term that we are trying to analyze the sentiment on.