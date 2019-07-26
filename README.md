# 641FNC-1
This is a single person project made by Hao Ye.

There were three models implemented ont this github repo. Please check the link for colab for the bert model. In this repo, you can find the implementation of Conditional encoder with attention, seperate BiLSTM then merge and merge then BiLSTM models.

Each model have been trained on same datasets, same length of data, same dropout rate and same epoch and batch size.

The Conditional encoder with attention achieved highest weighted score for 60% of result score. 

Code was implemented in Jupyter Notebook.

Glove have been used for embedding layer.

Tuning process was focus on dropout rate, difference of dropout layer and dropout attribute in LSTM, and length of the body.

Implementation of attention are referenced from https://inspiringpeople.github.io/data%20analysis/lstm_attention/
Link to bert implementation:
https://colab.research.google.com/drive/1WTs7xfb9mdLmaRG5CEr9UCo9NhRUJ6sB

