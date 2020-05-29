# intent_classification
Classifying the intention behind any comment broadly into five categories.
## Objective: 
Try to predict the intention behind a comment broadly into categories like
feedback, query, marketing, spam and news.
## Skill Path: 
Python, Machine Learning algorithms, Natural Language Processing.
## Abstract:
The dataset had comments from a number of websites and their corresponding intent (feedback, query, marketing, spam and news). The dataset had around 5000 sample comments. The data was split into test and training sets (2:8 ratio) and some text pre processing was done. Used Label Encode to encode categories and use Tf-Idf to vactorize the text data. The model was trained using grid search and 10 fold cross validation and Multinomial Naïve Bayes. The model achieved an accuracy of 94%.
