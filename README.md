# MentalHealthInSingapore

According to many statistics, Singaporeans are amongst the unhappiest in the world, and there is a concerning rise in mental health related issues amongst Singaporeans. Thus, in this project, we tackle the following research quesiton; what is the current state of emotional well-being in Singapore and how has COVID-19 affected it?

The project consists of the following three main objectives:

RQ1: How has the general mood of Singaporeans varied over the last 10 years (2010-2020) and what are the key factors affecting it?
RQ2: Examining the impact of Covid-19 on emotion state in Singapore in 2020
RQ3: Comparing and understanding the overall sentiment of Singapore and other countries due to Covid-19

In RQ1, we collected a sample of random English tweets geotagged to Singapore each month over a ten-year period between 2010 and 2020, to create a dataset consisting of 120000 tweets. Valence Aware Dictionary and sEntiment Reasoner (VADER) was used to classify the sentiment of the tweets, and wordclouds were used to visualise frequently tweeted words that are representative of a particular sentiment over a period of time. However, as VADER has low classification accuracy when it comes to Singlish tweets, which contain many slangs and colloquial terms, we trained our own Bidirectional Encoder Representations with Transformers (BERT) sentiment analysis model, by manually labelling over 2,500 tweets from a Singlish text corpus. The BERT model is able to classify the sentiment of tweets containing Singlish with a much higher accuracy compared to VADER, and the codes for the abovementioned analysis can be found in the RQ1 file. 




  
