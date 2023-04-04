## Machine-Learning-Projects

# Academic projects covering various ML algorithms. 

Projects are meant only for academic reference and in compliance with the graduate honors code.Please check the paths carefully before running the notebooks.

1- Logistics Regression implementation for message classification using NumPy.
   * Spam vs Ham text messages on UCI dataset
   * Implemented SGD,mini-batch GD 
   * Used binary cross-entropy loss function and tuned hyper-parameters for optimization
   * Built a logistic regression model in Numpy. Compared the performance of Stochastic Gradient Descent and Batch Gradient Descent.
   

2- Sentiment Analysis of IMDB movie reviews using Word2Vec model (skip-gram) in numpy and tensorflow
  * Used IMDB movie reviews in pickle format
  * Preprocessed ,Tokenized and embedded the dataset
  * Generated positive and negative data pairs
  * Implemented Word2Vec (skip-gram) using tensorflow , used Stochastic Gradient Descent
  
3-Semantic Network of tweets containing a keyword 
  * Scrapped tweets from twitter API
  * Cleaned, preprocessed the text by removing punctuations, stopwords and links
  * Built a semantic network of tweets containing a keyword
  * Made node size proportional to eigenvector centrality of words
 
4- N-gram and RNN based text generation model with Good turing and kneser ney smoothing
  * Cleaned,preprocessed and lemmatized the text
  * Created word tokens vacabulory
  * Calculated unigram and bigram count for the corpus
  * Implemented bi-gram model
  * Applied Good turing and KneserNey smoothing
  * Built an RNN model using tensorflow based on the same corpus and compared the performance with bi-gram model 
