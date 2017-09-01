# Teacher Review Sentiment Analysis

## Project Idea

This project is meant to flag professor evaluation comments that are not useful.
The original idea was to filter out inappropriate content (eg insults, threats, comments that could constitute sexual harassment).
We have expanded that original idea to also include flagging comments that do not contain constructive feedback (eg "cool")
We have included a training set of data, teacher reviews from [ratemyprofessors.com](http://www.ratemyprofessors.com/), which we have labelled with either a 1 or a 0, corresponding to useful or not useful.

Content of the Repo
------
#### Code

Classifier.ipynb
Classifier_SVC.ipynb
NB_Classifier.ipynb
ProfEvalsIR.ipynb

Different classifying algorithms that will take the training data contained in the csv files in ~/data/

RateMyProfessors Scraping.ipynb

Jupyter notebook with code that can scrape ratemyprofessors for reviews, which we used to build our dataset

#### Data

Labelled professor reviews:
/data/Evaluations-Binary.csv

Partially labelled professor reviews:
/data/Evaluations-Binary2_partially_labelled.csv

Professor reviews with student-determined quality rating for professor (awful, poor, average, good, awesome):
/data/rmp.csv
/data/scrapped_data_rmp.csv

Training data for a code that evaluates sentiment of tweets, from [cbrew's github](https://github.com/cbrew/Insults/blob/master/Insults/Data/Inputs/train.csv):
/data/train_sentiment.csv



![badge-img](https://img.shields.io/badge/Made%20at-%23AstroHackWeek-8063d5.svg?style=flat)