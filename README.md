# Teacher Review Sentiment Analysis

## Project Idea

This project is meant to flag professor evaluation comments that are not useful.
The original idea was to filter out inappropriate content (eg insults, threats, comments that could constitute sexual harassment).
We have expanded that original idea to also include flagging comments that do not contain constructive feedback (eg "cool")
We have included a training set of data, teacher reviews from [ratemyprofessors.com](http://www.ratemyprofessors.com/), which we have labelled with either a 1 or a 0, corresponding to useful or not useful.

### Content of the Repo

~/teacher-review-sentiment-analysis/ contains a number of different classifying algorithms that will take the training data contained in 
the csv files in ~/teacher-review-sentiment-analysis/data/ and create a model that can categorize other reviews as either useful or not useful.

Those notebooks are:
Classifier.ipynb
Classifier_SVC.ipynb
NB_Classifier.ipynb
ProfEvalsIR.ipynb

~/teacher-review-sentiment-analysis/ also contains an Jupyter notebook with code that can scrape ratemyprofessors for reviews, which we used to build our dataset.

That notebook is:
RateMyProfessors Scraping.ipynb

~/teacher-review-sentiment-analysis/data/ contains csv files which constitute our datasets.

Labelled professor reviews:
Evaluations-Binary.csv

Partially labelled professor reviews:
Evaluations-Binary2_partially_labelled.csv

Professor reviews with student-determined quality rating for professor (awful, poor, average, good, awesome):
rmp.csv
scrapped_data_rmp.csv

Training data for a code that evaluates sentiment of tweets, from [cbrew's github](https://github.com/cbrew/Insults/blob/master/Insults/Data/Inputs/train.csv):
train_sentiment.csv



![badge-img](https://img.shields.io/badge/Made%20at-%23AstroHackWeek-8063d5.svg?style=flat)