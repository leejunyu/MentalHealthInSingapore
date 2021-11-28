# MentalHealthInSingapore

According to many statistics, Singaporeans are amongst the unhappiest in the world, and there is a concerning rise in mental health related issues amongst Singaporeans. Thus, we tackled the following research quesiton in our project; what is the current state of emotional well-being in Singapore and how has COVID-19 affected it? 

Our research question consists of the following three objectives: (RQ1) How has the general mood of Singaporeans varied over the last 10 years (2010-2020) and what are the key factors affecting it? (RQ2) Examining the impact of Covid-19 on emotion state in Singapore in 2020 and (RQ3) Comparing and understanding the overall sentiment of Singapore and other countries due to Covid-19. 

We chose to collect data from the social media platform Twitter to answer these questions, as Twitter is mainly used for people to express their subjective opinions and emotions, which allows us to collect honest and unbiased opinions which truly reflect how users feel. 

In RQ1, we collected samples of random English tweets geotagged to Singapore over a ten-year period between 2010 and 2020. Sentiment analysis tools such as Valence Aware Dictionary and sEntiment Reasoner (VADER) and text2emotion were then used on this dataset to classify the sentiment of the tweets, and wordclouds to visualise frequently tweeted words representative of a particular sentiment over a period of time. However, as VADER has low classification accuracy for Singlish tweets, since they contain many slangs and colloquial terms, we trained our own Bidirectional Encoder Representations with Transformers (BERT) sentiment analysis model, by manually labelling over 2,500 tweets from a Singlish text corpus. The BERT model is able to classify the sentiment of tweets containing Singlish with a much higher accuracy compared to VADER. 

To better understand the determinants of happiness for Singaporeans, we referenced the World Happiness Report dataset collected by the United Nations between 2012 and 2020. We visualised this data, and performed simple regression analysis to understand the relationships between various determinants of happiness and the happiness score, for a better understanding of Singapore's happiness index score. The codes for this section can be found in the RQ1 file. 

In RQ2, we employed the same sentiment analysis tools as in RQ1 to examine the impact of Covid-19 on the emotional state of a representative sample of Singaporeans, based on the tweets posted by these Singaporeans over two time periods, one before Covid-19 and one during Covid-19. The codes for this section can be found in the RQ2 file.   

In RQ3, we compared the overall sentiment of Singapore with other countries, namely Malaysia and the UK, using tweets collected from users living in these countries. VADER and topic modelling using Latent Dirichlet Allocation (LDA) were used to understand the sentiment of tweets, and identify commonly discussed topics in each country respectively. The codes for this section can be found in the RQ3 file. 


  
