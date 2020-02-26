# BERT_sentences_classification

## Описание 
Основная задача новостного мониторинга - обрабатывать входящий поток новостей, находя в них интересные пользователям события. В задании предлагается построить модель для выявления в новости события, соответствующего задержке ввода некоторого объекта в эксплуатацию

## 
- Предложения, в которых речь идет о событии (tp.json)
- Предложения, в которых не содержится событие (tn.json)
- Новостной поток за несколько дней (test_data.json)

## Задача:
Найти в большом потоке новости, в которых есть информация о событии. 

Формат предоставления результатов:
- Файл с кодом и описанием алгоритма поиска релевантных новостей. В конце файла представлено ранжирование новостей. [Predicting_News.ipynb] https://github.com/maximenkooo/BERT_sentences_classification/blob/master/Predicting_News.ipynb 
- Файл с преобразованием данных и EDA [EDA.ipynb] https://github.com/maximenkooo/BERT_sentences_classification/blob/master/EDA.ipynb

Предсказание и основная работа с данным (файл) велась в Google Colab, поэтому доступ к данным определен по адресу "/content/drive/My Drive/nlp_test/data" и output and checkpoints соответственно "/content/drive/My Drive/nlp_test/bert_checkpoints" . Для того чтобы файл был воспроизводим локально данные пути должны быть изменены на "data" и "bert_checkpoints" соответственно.


