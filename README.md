# TDDE16-project - Influence of word embeddings for sentiment analysis

This project aims to test various word embeddings and their capability of influencing a task of sentiment analysis. The LSTM network is used as the main tool for performing the analysis. Pre-trained GloVe and fastText word embeddings were used; they were both fine-tuned and not fine-tuned. The result of the research is a short report NOT avaliable in this repo.

## Inspiration for model architecture

Following notebooks were a great inspiration for the project:

- https://www.kaggle.com/indira98/sentiment-analysis-of-coronavirus-tweets-with-lstm
- https://www.kaggle.com/adi996/covid-19-tweets-sentiment-prediction-lstm
- https://towardsdatascience.com/sentiment-analysis-using-lstm-and-glove-embeddings-99223a87fe8e

## Dataset

Tweets about COVID-19 can be downloaded from here: https://www.kaggle.com/datatattle/covid-19-nlp-text-classification

## Instructions

Short instructions for each block can be found in form of comments.

## Models

As training of all the models can take some time, so the models were saved locally and are not avaliable here due to repository's memory limits.

However, a short summary of every epoch for all the trained models can be found under `history/` and `history_frozen/` in respective `.csv` files.

## Evaluation

The output of every model evaluation can be found under Evaluation block in `sentiment_project.ipynb` notebook.
