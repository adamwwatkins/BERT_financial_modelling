# BERT_financial_volatility
Using BERT to Predict Financial Volatility

Adam Watkins' Thesis Sep 29 2021 

ReadMe

The data folder includes a few notebooks and prepared data files.

The headlines on which all of the following data is based can be found as:
headlines.csv


REQUIRED FOR EMBEDDINGS EXPERIMENT

exp1_bert_embeddings.npy
are the combined BERT embeddings created from the concatenated daily headlines

exp1_cont_targets.csv
are the daily difference values for the VIX which correspond to exp1_bert_embeddings.npy

exp1_glove_embedding_matrix.npy
is the GloVe embedding matrix which corresponds to the train set of headlines

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

