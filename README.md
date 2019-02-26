# PSTAT-135-Winter-19-Final-Project


## Overview 

Modeling:
Do both supervised and unsupervised 

baseline -- supervised, create dummy variables for all categories, and then predict the categories   
  NOTE: leave out categories with less than 20 observations in them


complex -- unsupervised, clustering to group categories together




### In Jeopardy_SA.pynb
Read in the Dataset.   
Removed unnecessary punctuation in questions.   
Tokenized questions.   
Removed stop words from questions.   


Useful link for preprocessing in spark: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3923635548890252/1357850364289680/4930913221861820/latest.html


Code used for word cloud:
http://www.sthda.com/english/wiki/text-mining-and-word-cloud-fundamentals-in-r-5-simple-steps-you-should-know

https://github.com/chezou/mecab-on-pyspark/blob/master/word_cloud.py

Cost function:

https://rsandstroem.github.io/sparkkmeans.html


TO DO: 

Look at purity metric for Bisecting K means example : BKM 145

Figure out how to do the pipeline, crossvalidation

Need one more visualization

Sensitivity Analysis

Final Writeup/Powerpoint Presentation



