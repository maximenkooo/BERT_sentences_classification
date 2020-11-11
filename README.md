# BERT_sentences_classification

## Description 
The main task of news monitoring is to process the incoming news stream, finding the events interesting to users. The task involves building a model to identify the event in the news, corresponding to the delay in putting some object into operation.

## Data
- sentences concerning the event (tp.json)
- sentences that do not contain an event (tn.json)
- news stream for several days (test_data.json)

## Task:
Find in a large stream of news, which have information about the event. 

Format for presenting results:
- File with code and description of algorithm for searching relevant news. At the end of the file you can see the ranking of news. [Predicting_News.ipynb] https://github.com/maximenkooo/BERT_sentences_classification/blob/master/Predicting_News.ipynb 
- Data Conversion File and EDA [EDA.ipynb] https://github.com/maximenkooo/BERT_sentences_classification/blob/master/EDA.ipynb

Prediction and the main work with the data (files) was carried out in Google Colab, so access to the data is determined by the address "/content/drive/My Drive/nlp_test/data" output and checkpoints respectively "/content/drive/My Drive/nlp_test/bert_checkpoints" . In order for a file to be locally reproduced, path data must be changed to "data" and "bert_checkpoints" respectively.


