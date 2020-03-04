# Sentiment Analysis




### Document Level Sentiment Analysis
------------------------------------------------

The basis unit of information is a single document of opinionated text. In this type of document level classfication a single review about a single topic is considered. But in case of forumns or blogs, comparative sentences may appear and consumers may compare one product with other that has similar characteristics and hence document level analysis is not desirable in forums or bogs.

* While doing docoument level classficiation irrelevant sentences must be eliminated at preprocessing phase.
* For document level classification both suprevised and unsupervised machine learning classifications methods are used.
* Supervised machine learning such as SVM, Naive Bayes, KNN and Maximum Entropy can be used to train the system

For document level classification both supervised and unsupervised machine learning classification methods are used. Supervised machine learning algorithm such as Support Vector Machine (SVM), Naive Bayes, KNN and Maximum Entropy can be used to train the system

### Entity or Aspect Level Sentiment Analysis
------------------------------------------------

The entity or aspect level sentiment analysis performs finer-grained analysis. The goal is to find out the sentiment on entites or aspect of these entities.
> My Xperia Z2 has good picture quality but it has less battery backup

So, the opinion on Sony's camera and display quality is *positive*           but the opinion on Sony's battery is *negative*


### Phrase Level Sentiment Analysis
------------------------------------------------

* The phrase that contains opinion words are found out and a phrase level classification is done

(phrase: a red box, will go, quite big, very slowly)

> advantageous: where the exact opinion about an entity can be correctly extracted
> disadvantageos: where contextual polarity matters

* Contextual polarity: words that surround other words
* Paper uses Parts of Speech (POS) polarity
* Tree Kernel technique

Research work uses two types of resources such as > hand dictionary of emotions < and dictionary collected from web

Six different sentiments can be analyzed using sentiment analysis package namely *anger, disgust, fear, joy, sadness and surprise*

* anger
* disgust
* fear
* joy
* sadness
* surprise

### Sentence Level Sentiment Analysis
------------------------------------------------
Here the polarity of each sentence is calculated and then same document level classification methods are used for the sentecne level classification problem. Then the objective and subjective sentences must be found out. The subjective sentences must contain opinion words which help in determining the sentiment about entity. After that polarity classification is done into positive, negative and neutral classes. This feature can be uncertain and non-grammar online reviews.
```
#For example: Consider the following comment
* I like the high res *
Here, "res" refers to resolution and resolution to similar to graphics

Sentiments, textual reviews may contain mixture sentiment.

#For example : " I like the graphics, but it takes battery a lot"

* graphics = positive
* battery life = negative
```

## Machine Learning Techniques

A training datasets is used to learn the documents and test dataset is used to validate the performance. There are number of machine learning algorithms used to classify reviews.

There are two types:
--------------------
Link: https://github.com/bastolasushan/machine_learning_notes

* Supervised Machine Learning
  * Maximum Entropy
  * SVM
  * Naive Bayes
  * KNN
  
* Unsupervised Machine Learning
  * HMM
  * Neural Networks
  * PCA
  * ICA
  * SVD
