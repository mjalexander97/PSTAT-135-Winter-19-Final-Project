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

Figure out baseline and complex models -- need to figure out one more supervised model

Figure out how to join Human Defined Clusters with datasets of 145 categories -- DONE; run below:  
Run Naive Bayes on this . 
Run Bisecting K-means . 

Look at purity metric for Bisecting K means example : BKM 145 -NO

Word Clouds for clusters for BKM/NB  

Sensitivity Analysis -- change seeds and run multiple CV   

Final Powerpoint Presentation



