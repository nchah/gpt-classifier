# GPT-classifier

A fun experiment with few-shot learning to use GPT as a classifier.

## Instructions

- Running this will require API keys from OpenAI's GPT models. For security, I'm not able to share the keys I used here.
- This notebook contains all of the code and evaluation results for the few-shot learning experiment with GPT.


## Info
Datasets:
- Using the AG's News Topic Classification Dataset
- AG is a collection of more than 1 million news articles. News articles have been gathered from more than 2000 
news sources by ComeToMyHead in more than 1 year of activity. ComeToMyHead is an academic news search engine which 
has been running since July, 2004. 
- URL: https://github.com/mhjabreel/CharCnn_Keras/tree/master/data/ag_news_csv

Some stats:
```
$ wc -l ag_news_csv/*.csv
    7600 ag_news_csv/test.csv
  120000 ag_news_csv/train.csv
  127600 total
```
