#Using BERT to Predict Financial Volatility

Adam Watkins' Thesis
Sep 29 2021
HU Berlin

This thesis is comprised of 2 experiments:

The first compares the performance of concatenated relevant financial news headlines to predict daily changes in the VIX open and close price. Headlines are turned into GloVe and BERT embeddings to see which performs better in an ANN.

The second compares two models, one with traditional technical and fundamendental indicators, and another with the addition of two versions of BERT sentiment indices. The goal is to see if BERT sentiment indices improve predictive power of the model.


The headlines on which all of the following data is based can be found as:
headlines.csv


REQUIRED FOR EMBEDDINGS EXPERIMENT

exp1_bert_embeddings.npy
are the combined BERT embeddings created from the concatenated daily headlines

exp1_cont_targets.csv
are the daily difference values for the VIX which correspond to exp1_bert_embeddings.npy

exp1_train_ind.npy
is the train index of the headlines

exp1_test_ind.npy
is the test index of the headlines

exp1_test_labels.csv
are the classification labels for the test set.

exp1_train_labels.csv
are the classification labels for the train set.

exp1_train_padded.npy
are the padded training GloVe inputs. 

exp1_test_padded.npy
are the padded test GloVe inputs. 



REQUIRED FOR SENTIMENT INDEX EXPERIMENT

exp2data.csv
This contains all fundamental, technical and index features and target for the experiment.

