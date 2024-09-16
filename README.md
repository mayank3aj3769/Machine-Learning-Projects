## Deep-Learning-Projects

# Academic projects covering various applications of Deep Learning

Projects are meant only for academic reference and in compliance with the graduate honors code.Please check the paths carefully before running the notebooks.

1- **[Logistics Regression implementation for message classification using NumPy](https://github.com/mayank3aj3769/Machine-Learning-Projects/blob/9e7952cbcf416d7dfec519635ae52756dce438a0/Logistic%20Regression%20for%20text%20classification%20in%20Numpy.ipynb)**
   * Spam vs Ham text messages on UCI dataset
   * Implemented SGD,mini-batch GD 
   * Used binary cross-entropy loss function and tuned hyper-parameters for optimization
   * Built a logistic regression model in Numpy. Compared the performance of Stochastic Gradient Descent and Batch Gradient Descent.
   

2- **[Sentiment Analysis of IMDB movie reviews using Word2Vec model (skip-gram) in numpy and tensorflow](https://github.com/mayank3aj3769/Machine-Learning-Projects/blob/9e7952cbcf416d7dfec519635ae52756dce438a0/Logistic%20Regression%20for%20text%20classification%20in%20Numpy.ipynb)**
  * Used IMDB movie reviews in pickle format
  * Preprocessed ,Tokenized and embedded the dataset
  * Generated positive and negative data pairs
  * Implemented Word2Vec (skip-gram) using tensorflow , used Stochastic Gradient Descent
  
3-**[Semantic Network of tweets containing a keyword](https://github.com/mayank3aj3769/Machine-Learning-Projects/blob/0cc2255ca1ef89e030a81906abf47a72deef0176/Semantic%20Network%20based%20on%20tweets%20containing%20a%20keyword.ipynb)** 
  * Scrapped tweets from twitter API
  * Cleaned, preprocessed the text by removing punctuations, stopwords and links
  * Built a semantic network of tweets containing a keyword
  * Made node size proportional to eigenvector centrality of words
 
4- **[N-gram and RNN based text generation model with Good turing and kneser ney smoothing](https://github.com/mayank3aj3769/Machine-Learning-Projects/blob/0cc2255ca1ef89e030a81906abf47a72deef0176/N-gram%20and%20RNN%20based%20language%20model%20for%20text%20generation.ipynb)**
  * Cleaned,preprocessed and lemmatized the text
  * Created word tokens vacabulory
  * Calculated unigram and bigram count for the corpus
  * Implemented bi-gram model
  * Applied Good turing and KneserNey smoothing
  * Built an RNN model using tensorflow based on the same corpus and compared the performance with bi-gram model 
  
5- **[Lexical Complexity Score Predictor of single words as per SemEval-2021 task](https://github.com/mayank3aj3769/Machine-Learning-Projects/tree/0cc2255ca1ef89e030a81906abf47a72deef0176/Lexical%20Complexity%20Score%20Predictor%20using%20a%20BERT%20Based%20model)** https://sites.google.com/view/lcpsharedtask2021 
  * Predicted lexical complexity score of a word in a sentence using a transformer based deep learning model
  * Pre-processed the tokens by removing special characters, expanded the contractions, eliminating stop words, performed stemming and lemmatization on the tokens using ‘nltk’ library
  * Model architecture used pretrained BERT and RoBERTa model followed by a series of 6 linear layers. Used ‘RMSProp’ as optimizer and obtained mean-absolute-error of 0.0947
  * Demonstrated the performance on test set using an inference model

6- **[A Neural Network model of Semantic Cognition -- by Rogers and McClleland](https://github.com/mayank3aj3769/Machine-Learning-Projects/blob/0cc2255ca1ef89e030a81906abf47a72deef0176/A%20Neural%20Network%20model%20of%20Semantic%20Cognition.ipynb)**
  * This notebook explores a neural network model of semantic cognition to model aspects of semantic cognition with a multi-layer neural network, which contrasts with classic symbolic approaches for organizing semantic knowledge.
  * Trained Neural Network to map objects to their corresponding properties.
  * Deterioration of semantic knowledge in dementia is accounted by adding noise to the learned representations.
  * Network is trained to answer queries involving an item (e.g., “Canary”) and a relation (e.g.,  “CAN”), outputting all attributes that are true of the item/relation pair (e.g., “grow, move, fly, sing”).

7- **[Sentiment Analysis of market conditions based on global news reports](https://github.com/mayank3aj3769/Machine-Learning-Projects/blob/0cc2255ca1ef89e030a81906abf47a72deef0176/Sentiment%20analysis%20of%20IMDB%20reviews%20using%20word2vec%20in%20np%20and%20tf.ipynb)**
  * Developed a sentiment analysis system for specific set of industries by utilizing the massive volume of online news stories.
  * Scraped the news articles from global media platforms using the newsdata.io API and stock market data using yahoo finance API
  * Pre-processed the dataset by removing stop words and performing lemmatization and stemming.
  * Visualized the dataset using the WordCloud and frequency distribution plots for each cluster
  * Labelled the articles using VADER sentiment analyzer package and built a transformer based model consisting of pre-trained      weights of BERT, RoBERTa and linear layers.Used mean-squared-error as loss function and RMSProp as optimizer.
  * Used L2-regularization and dropout mechanism to prevent overfitting.
  * Finally obtained the pearson correlation score of 0.87 between average stock price and  sentiment score of a sector to validate the results 

8- **[Classification and Representation Lexical classes using language modelling approach](https://github.com/mayank3aj3769/Machine-Learning-Projects/blob/0cc2255ca1ef89e030a81906abf47a72deef0176/Classification%20and%20representation%20of%20lexical%20classes%20using%20Language%20Modelling%20approach.ipynb)**

  * Extended Elman's "Finding Structure in Time" using a transformer-based language model on the 'go-emotion' text corpus for advanced lexical and grammatical analysis, validating Elman's model against this larger dataset and identifying limitations through post-training embedding studies.

  * Introduced a transformer model, examining its embeddings for semantic patterns using cosine similarity and pairwise distances among prevalent tokens.

  * Compared semantic cognition insights from this investigation with those of Rogers and McClelland's methodology, providing a consolidated view of language modeling's ability to classify and represent lexical   information.