Assignment - text classification
Programming Project – Classification of questions in the travel domain

 
Introduction

In this programming assignment, you should implement the following text classification systems for the given data set. The attached paper explains the data set, and sets the baseline. 

1. A traditional ML classifier s.a. SVM or Logistic Regression with at least 5  of the features mentioned in the paper.

2. A traditional ML classifier s.a. SVM or Logistic Regression with word embedding features s.a. word2vec or fasttext.

3. A NN classifier s.a. an LSTM for classification

4. BONUS - experiment with a BERT-based classifier

Use 10-fold cross validation to evaluate your model.  Record precision, recall, and F-score of each of the dialog act in the corpus, and the accuracy and the confusion matrix of the classifiers.  Compare the results of the three classifiers.

A python script containing the code (all code should be in one script) with clear execution instructions  should be provided.
Deliverables

 A written report that describes:

    How the corpus was pre-processed
    The features used for classification, how feature extraction was carried out, how word embeddings are retrieved and used (i.e describe your code briefly)
    How cross-validation is implemented
    How the classifiers are implemented
    How evaluation measurements are taken
    Evaluation Results
    Discussion on the best performing feature set and classifier

Each of these descriptions should be accompanied with the line numbers of the corresponding code in the Python script, for cross-checking when marking the assignment.

