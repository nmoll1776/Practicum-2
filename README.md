# Practicum-2 Regis University - MSDS 696 - Nick Molliconi

Social Media & Eating Disorders: Measured through Sentiment and Correlation Analysis

Background:

Eating disorders is defined as a disease that impacts both the mental and physical human aspect of those suffering and there are several different types of eating disorders, such as anorexia nervosa, bulimia and orthorexia.  Within the United States alone, there are over thirty (30) million Americans who suffer from an eating disorder, which encompasses twenty (20) million females and ten (10) million males (Valex, 2021). 

Research:

Through sentiment analysis, I wanted to get a sense of feelings around eating disorder social media tweets, as my initial bias is that it is negative.  Additionally, looking into any possible correlation between negative tweet sentiment and those who have over 1 million followers.  From there, and on the second dataset, looking at global prevalence to visually display how large of a problem this is.  I utilized two different data sets from Kaggle around eating disorders. My bias, based on my own journey/experience, and perception of social media impacts on those with eating disorders, is that a majority of social media tweets will be negative, especially with those who have over 1 million followers.  Additional bias includes that prevalence rates are continuing to increase and that there is a correlation between negative tweet sentiment and increasing prevalence rates. 

There were a few challenges to this study around the two datasets.  The first challenge was around the social media tweet dataset and the column that had.
geolocation (longitude/latitude).  Out of the 490,000+ rows, less than .008% had any location attributes.  The rest were either blank or filled with free text.  This shifted my initial hypothesis from testing a relationship on location and tweet sentiment within this dataset alone.  This was achieved through combining the datasets, tweet and prevalence, but the challenge was not knowing if the timeframes between the two datasets aligned (years).  The second challenge was with the prevalence dataset in that it was dated data.  The latest data, which was complete, was for 2013.  This focused my attention on the time period of 2009-2013.

Two datasets were used in this study, both from Kaggle.com.  The first dataset was social media tweet data categorized around the topic of eating disorders.
with over 490,000 lines of tweets.  The second dataset was eating disorder global prevalence data by year, country, male and female.  I focused my analysis, within the tweet dataset to columns that included the tweets and number of followers.  Within the prevalence dataset, I focused on the columns of total population and prevalence percentage. A random sample was taken from the social media tweet dataset of around 1% = 4,900 (est.) tweets.  I also focused on followers > and < 5,000 followers. Within the prevalence dataset, eight (8) nations were selected, based on their respective higher prevalence rates, compared to other nations, and then grouped between nations in the Western Hemisphere (United States, Canada, Mexico and Brazil) and Eastern Hemisphere (China, India, Nigeria and Russia).

Below are the links to both datasets:

Eating Disorder Tweets: https://www.kaggle.com/datasets/jabenitez88/eating-disorders-tweets
Prevalence-of-eating-disorders-in-males-vs-females: https://www.kaggle.com/datasets/valchovalev/prevalenceofeatingdisordersinmalesvsfemales

Research Hypotheses:

H0: There is no significant correlation between users with over five thousand followers and negative tweet sentiment.

H0: There is no significant correlation between users with over five thousand and positive tweet sentiment.

H0: There is no significant correlation between 2009-2013 total prevalence population (United States, Canada, Mexico, Brazil) and negative and neutral tweet sentiment.

H0: There is no significant correlation between 2009-2013 total prevalence population (Russia, Nigeria, India, China) and negative and neutral tweet sentiment.

Visualizations:

Word cloud on tweet data:

![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/4d351197-b25e-4a59-91ee-93130b83a4ef)

Boxplot on Number of Tweet Followers:

![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/c1d73a4f-466a-45b1-adfe-33eff85eae93)

Prevalence of Eating Disorders:

![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/db83d91f-16ab-4a37-94aa-d3edd820d96d)


![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/0e2fdb61-2666-48fd-8467-6738744764ed)


![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/272a3289-40e6-4b18-8170-7c3957c2b07e)

Results:

Vader Sentiment Analysis:
![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/d332ee2f-bffa-42b1-b822-835a222cb981)

Tweet Sentiment Analysis:
![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/3ad95810-0aae-4fc6-becd-4ceb9bf0acda)

Tweet & Sentiment Analysis:
![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/7984b016-0e40-42cd-a535-170ea200d702)

Resources:

Eating Disorder Information: https://www.nationaleatingdisorders.org/what-are-eating-disorders

Emergency/Crisis: Dial 988 or text Crisis Text Line by texting “NEDA” to 741741

LinkedIn: https://www.linkedin.com/in/nick-molliconi-mba-ms-46b74619/

References:

Alberto, J., Andrades, B. (2021). Eating Disorder Tweets. www.kaggle.com. Retrieved on October 23, 2023 from https://www.kaggle.com/datasets/jabenitez88/eating-disorders-tweets.
 
Alex,. (2017, October 18). Python geopy get city and country.  www.stackoverflow.com. Retrieved on November 7, 2023 fromhttps://stackoverflow.com/questions/46809525/python-geopy-get-city-and-country. 
 
Aakarsha_Chugh,. (2023, April, 18). Label Encoding in Python. www.geeksforgeeks.com. Retrieved on November 17, 2023 from https://www.geeksforgeeks.org/ml-label-encoding-of-datasets-in-python/. 
 
Ankthon,. (2021, October 7). Python | Sentiment Analysis using VADER. www.geeksforgeeks.com. Retrieved on November 1, 2023 from https://www.geeksforgeeks.org/python-sentiment-analysis-using-vader/.

Ekern, J,. MS, LPC. The National Eating Disorders Association (NEDA). www.eatingdisorderhope.com.  (2021, January 6). Retrieved on November 25, 2023 from https://www.eatingdisorderhope.com/information/help-overcome-eating-disorders/neda.
 
George, N. PhD. (2019, November 6). Week 2 Assignment Walkthrough. www.youtube.com. Regis University. https://www.youtube.com/watch?v=NaeyhIBIJZE.
 
Huerta, J. (2022, April 14). Python: re.sub('[^A-Za-z]', ' ', string) for a list. www.stackoverflow.com. Retrieved on October 29, 2023 from https://stackoverflow.com/questions/71878621/python-re-suba-za-z-string-for-a-list.  
 
Jacobperalta,. (2023, November 24). www.geeksforgeeks. Text Preprocessing in Python. Retrieved on October 28, 2023 from https://www.geeksforgeeks.org/text-preprocessing-in-python-set-1/. 
 
Mchangun,. (2013, October 24). Faster way to remove stop words in Python. www.stackoverflow.com. Retrieved on October 29, 2023 from https://stackoverflow.com/questions/19560498/faster-way-to-remove-stop-words-in-python.
 
mGalarnyk. (2018). Python_Tutorials/Statistics/boxplot
/Box_plot_interpretation.ipynb. www.github.com. Retrieved on November 25, 2023 from https://github.com/mGalarnyk/Python_Tutorials/blob/master/Statistics/boxplot/Box_plot_interpretation.ipynb. 

n.a. (2019, March 31). Remove meaningless words from dataframe column. www.stackoverflow.com. Retrieved on November 7, 2023 from https://stackoverflow.com/questions/55443298/remove-meaningless-words-from-dataframe-column.

n.a. (2022). What are eating disorders? www.nationaleatingdisorders.org. Retrieved on November 25, 2023 from https://www.nationaleatingdisorders.org/what-are-eating-disorders.![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/52baee9f-f19a-4c9f-898b-51cc554e36ec)

Sidani JE, Shensa A, Hoffman B, Hanmer J, Primack BA. The Association between Social Media Use and Eating Concerns among US Young Adults. J Acad Nutr Diet. 2016 Sep;116(9):1465-1472. doi: 10.1016/j.jand.2016.03.021. Epub 2016 May 5. PMID: 27161027; PMCID: PMC5003636.
 
Tyle, K. (2023). Interactive data visualization in Python: Geopandas. www.atmos.albany.edu. Retrieved on November 3, 2023 from https://www.atmos.albany.edu/facstaff/ktyle/atm533/core/week4/geopandas.html#:~:text=You%20can%20do%20this%20before%20starting%20the%20Python,Shapely%20by%20default%2C%20even%20if%20PyGEOS%20is%20installed.

Valex, V. (2021). Prevalence of eating disorders in males vs females. www.kaggle.com. Retrieved on October 23, 2023 from https://www.kaggle.com/datasets/valchovalev/prevalenceofeatingdisordersinmalesvsfemales.

Vu, D. (2023, February). Generating WordClouds in Python Tutorial. www.datacamp.com. Retrieved on October 30, 2023 from https://www.datacamp.com/tutorial/wordcloud-python. 

Yamuca, L. (2021, April 30). How to use t.ppf()? which are the arguments?  www.stackoverflow.com. Retrieved on November 23, 2023 from https://stackoverflow.com/questions/67340028/how-to-use-t-ppf-which-are-the-arguments. 
![image](https://github.com/nmoll1776/Practicum-2/assets/106831989/274f8956-0f1e-4280-83fb-5baec63689b5)













