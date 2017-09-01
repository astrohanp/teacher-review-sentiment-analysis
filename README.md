# Teacher Review Sentiment Analysis

## Project Idea

This project is meant to flag professor evaluation comments that are not useful.
The original idea was to filter out inappropriate content (eg insults, threats, comments that could constitute sexual harassment).
We have expanded that original idea to also include flagging comments that do not contain constructive feedback (eg "cool")
We prepared a set of training data by scrapping teacher reviews from [ratemyprofessors.com](http://www.ratemyprofessors.com/), which were labelled with either a 1 or a 0, corresponding to useful or not useful.

Content of the Repository
------
#### Notebooks
This folder contains the jupyter notebooks. It has the following files :

* **Classifier_SVC** - Classifying reviews using Support Vector Machines
* **NB_Classifier_tb** - Classifying reviews using a Naive Bayes Classier(with textblob)
* **NB_Classifier** - Classifying reviews using a Naive Bayes Classifier
* **ProfEvalR** - Alternate technique for using NBC to evaluate performance
* **RateMyProfessors Scraping** - Notebook used to scrape data


#### Data
This folder contains data used for the training.

* **Evaluations-Binary.csv** - Labelled professor reviews(155)
* **Evaluations-Binary2_partially_labelled.csv** - Partially labelled professor reviews(2504-total, 566-labelled)
* **current_data.csv** - Labelled professor reviews(566)
* **rmp.csv** - Professor reviews with student-determined quality rating for professor (awful, poor, average, good, awesome)
* **scrapped_data_rmp.csv**- Raw scrapped data from RMP
* **train_sentiment.csv** - Training data for a code that evaluates sentiment of tweets, from [cbrew's github](https://github.com/cbrew/Insults/blob/master/Insults/Data/Inputs/train.csv)



Feel free make improvements by forking this repo!

![badge-img](https://img.shields.io/badge/Made%20at-%23AstroHackWeek-8063d5.svg?style=flat)