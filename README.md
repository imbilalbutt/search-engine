# search-engine
This stuff related to Information Retrieval course which was being offered to FAST-NUCES Lahore.

# Assignment 1:

The first assignment is all about reading html files, removing their headers and parsing them.
And make inverted index out of it.
Inverted index is basically the term_id and all of occurance documents along with the positions in
each document.

# Assignment 2:

The second part consists of assigning scores to documents on basis of relevance. In this assignment
two methods are implemented
1- Okapi BM25
2- Dirichlet Smoothing

# Assignment 3:

The purpose of question 1 is to train word2Vec using genism on dataset. For this we will have to read input file and 
then preprocess (tokenization, etc) data using nltk (as done in HW1) or genism and then train wordtoVec on dataset.

The purpose of question 2 is to build a sentiment classifier using the Naive Bayes classification techniques and a bag of
words model. I will implement following 2 models for sentiment analysis and will report accuracies of both models.

1. Bag of words based on raw counts
2. Bag of words based on TfIDF
