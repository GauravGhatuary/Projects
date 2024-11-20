# Data Science Projects
## Twitter Sentiment Analysis
This is a project to analyze Twitter sentiments based on real-world tweets.The data has been taken from 'Tweet Sentiment Extraction' -a Kaggle competition 'https://www.kaggle.com/competitions/tweet-sentiment-extraction'.

Since tweets often involve informal language as well as combination of different objects like emojis, phone nos, URLs etc, various pre-processing techniques were applied to produce cleaed text which can be vectorized.

Finally , 3 types of vectorization and modelling techniques have been used to predict the tweet sentiments which produced following accuracy:
  Using gloVe embeddings and trained upon Bidirectional LSTM- 72% accuracy
  Using ELMo embeddings and trained upon Bidirectional LSTM- 75% accuracy
  Using DistilBERT Text Classification based on Transformer from hugginface- 78% accuracy

## Population  Estimate Model
This is a project to estimate the population growth rate of various countries  based on  various population indicators of previous years.The data has been taken from 'World Bank Databank'.

The population estimate model worked best when using a multi-layer LSTM architecture, that takes multiple demographic features as input, and can produce prediction for future population with mean error rate of 2% for 5 years into future and 5% for 10 years in future.

The model was trained upon progressive timeseries of demographic features, that is data for all previous years was considered as input features, and target was set as population growth for 5th and 10th year from the last year in the dataset.

## PCB Defect
This is a project to identify and classify the various types of defects that occur in Printed Circuit Boards.## Population  Estimate Model
https://www.kaggle.com/code/gauravghatuary/pcb-defecthttps://www.kaggle.com/code/gauravghatuary/pcb-defect

The population estimate model worked best when using a multi-layer LSTM architecture, that takes multiple demographic features as input, and can produce prediction for future population with mean error rate of 2% for 5 years into future and 5% for 10 years in future.

The population estimate model worked best when using a multi-layer LSTM architecture, that takes multiple demographic features as input, and can produce prediction for future population with mean error rate of 2% for 5 years into future and 5% for 10 years in future.


## Predictive Maintainance Milling Machine
This is a project to predict the failures in milling machine taken from a  Kaggle dataset-'https://www.kaggle.com/datasets/stephanmatzka/predictive-maintenance-dataset-ai4i-2020'
Since the failures were rare , the dataset was balanced using oversampling techniques from Imbalanced-learn package.The model utilized Tree-based Ensemble Boosting techniques to make the prediction for each type of failure.
