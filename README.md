# Practicum-2 Regis University - MSDS 696 - Nick Molliconi

Social Media  & Eating Disorders: Measured through Sentiment and Correlation Analysis

Background:

Eating disorders is defined as a disease that impacts both the mental and physical human aspect of those suffering and there are several different types of eating disorders, such as anorexia nervosa, bulimia and orthorexia.  Within the United States alone, there are over thirty (30) million Americans who suffer from an eating disorder, which encompasses twenty (20) million females and ten (10) million males (Valex, 2021). 

Research:

Through sentiment analysis, I wanted to get a sense on feelings around eating disorder social media tweets, as my initial bias is that it is negative.  Additionally, looking into any possible correlation between negative tweet sentiment and those who have over 1 million followers.  From there, and on the second dataset, looking at global prevalence to visually display how large of a problem this is.  I utilized two different data sets from Kaggle around eating disorders. My bias, based on my own journey/experience, and perception of social media impacts on those with eating disorders, is that a majority of social media tweets will be negative, especially with those who have over 1 million followers.  Additional bias includes that prevalence rates are continuing to increase and that there is a correlation between negative tweet sentiment and increasing prevalence rates. 

There were a few challenges to this study around the two datasets.  The first challenge was around the social media tweet dataset and the column that had
geolocation (longitude/latitude).  Out of the 490,000+ rows, less than .008% had any location attributes.  The rest were either blank or filled with free text.  This shifted my initial hypothesis from testing a relationship on location and and tweet sentiment within this dataset alone.  This was achieved through combining the datasets, tweet and prevalence, but the challenge was not knowing if the timeframes between the two datasets aligned (years).  The second challenge was with the prevalence dataset in that it was dated data.  The latest data, that was complete, was for 2013.  This focused my attention to the time period of 2009-2013.

Below are the 

Research Hypotheses:

H0: There is no significant correlation between users with over five thousand followers and negative tweet sentiment

H0: There is no significant correlation between users with over five thousand and positive tweet sentiment

H0: There is no significant correlation between 2009-2013 total prevalence population (United States, Canada, Mexico, Brazil) and negative and neutral tweet sentiment

H0: There is no significant correlation between 2009-2013 total prevalence population (Russia, Nigeria, India, China) and negative and neutral tweet sentiment.

Data:

Two datasets were used in this study, both from Kaggle.com.  The first dataset was social media tweet data catorigized around the topic of Eating Disorders
with over 490,000 lines of tweets.  The second dataset was Eating Disorder global prevelance data by year, country, male and female.  I focused my analysis, within the tweet dataset to columns that included the tweets and number of followers.  Within the prevelence dataset, I focused on the columns of total population and prevalence percentage. A random sample was taken from the social media tweet dataset of aound 1% = 4,900 (est.) tweets.  I also focused on followers > and < 5,000 followers. Below are the links to both datasets:
  
Eating Disorder Tweets: https://www.kaggle.com/datasets/jabenitez88/eating-disorders-tweets
Prevalence-of-eating-disorders-in-males-vs-females: https://www.kaggle.com/datasets/valchovalev/prevalenceofeatingdisordersinmalesvsfemales

Challenges:



  
  Prevalence Data:
  
    2009-2013
    Eight nations: US, Brazil, Canada, Mexico, Russia, China, Nigeria & India


