# The Askeladden Algorithm 

W207 | Applied Machine Learning | Spring 2019

Team Troll Trappers: Laura Pintos, Ramiro Cadavid, and Anna Jacobson

## Introduction

In February 2019, as part of special counsel Robert Mueller’s investigation of the Russian government's efforts to interfere in the 2016 presidential election, the United States Department of Justice charged 13 Russian nationals with illegally meddling in American political processes. The defendants worked for a well-funded “troll factory” called the Internet Research Agency (IRA), which reportedly had 400 employees, or “trolls”, working 12-hour shifts from a nondescript business center in St. Petersburg. The IRA ran a sophisticated, coordinated campaign to spread disinformation and sow discord into American politics via social media, often Twitter.

Twitter has identified and suspended thousands of these malicious accounts, deleting millions of the trolls’ tweets from public view on the platform. While other news outlets have published samples, it has been difficult to understand the full scale and scope of the IRA’s efforts, as well as the details of its strategy and tactics. According to Alina Polyakova, a foreign policy fellow at the Brookings Institution, “Wiping the content doesn’t wipe out the damage caused, and it prevents us from learning about how to be better prepared for such attacks in the future.” To address this problem, and “in line with our principles of transparency and to improve public understanding of alleged foreign influence campaigns,” Twitter has now made publicly available archives of Tweets and media that it believes resulted from potentially state-backed information operations.

According to a December 2018 United States Senate Select Committee on Intelligence briefing, there were approximately 109 Twitter accounts masquerading as news organizations, including U.S. local news organizations. The 44 U.S.-related accounts had amassed 660,335 followers between them, with an average of 15,000 followers. Many of these accounts behaved similarly, posting links to articles and local content dozens of times per day.

The purpose of this project is to develop a machine learning algorithm to predict "fake news" troll tweets. Our algorithm is named after Askeladden, a boy in Norwegian folklore who outwits trolls.

## Repo Contents

### 1. W207 Final Project - The Askeladden Algorithm.ipynb
This is the main notebook for the project.

### 2. W207 Final Project - Real News Scrape.ipynb
This notebook includes the script for scraping Twitter for the real news tweets. Utilizes Hardvard Dataverse's News Outlet Tweet Ids dataset (<https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/2FIFLH>) for Tweet IDs. 

### 3. W207 Final Project - Initial Dataset Creation.ipynb
This notebook includes the processing of the two original datasets (troll tweets and real news tweets) into the combined dataset used in the main notebook.

### 4. W207 Final Project - Production Pipeline.ipynb
This notebook includes the production pipeline for parameter optimization using GridSearchCV.

### 5. W207 Final Project - Presentation.pdf
Slide deck from in-class presentation of project.

### 6. Data
a. real_news_wfox.csv - The real news dataset, used in the Initial Dataset Creation notebook.  
b. news_tweets_big.csv - The combined real/troll news dataset, used in the main notebook.

Note that ira_tweets_english.csv (the troll dataset, used in the Initial Dataset Creation notebook), as well as the original troll tweet dataset published by Twitter (https://about.twitter.com/en_us/values/elections-integrity.html#data) from which it was created, are not included in this repo due to GitHub's file size limitations.

## References

https://fivethirtyeight.com/features/why-were-sharing-3-million-russian-troll-tweets/

https://fivethirtyeight.com/features/what-you-found-in-3-million-russian-troll-tweets/

https://www.nytimes.com/2018/02/18/world/europe/russia-troll-factory.html

https://www.bloomberg.com/features/2016-how-to-hack-an-election/?fbclid=IwAR1tHKfzgeme-K_ZH8tdpBeAhLB3ZFNrlj7bXCQD70sthqbjFalKmNCappA

https://www.hsdl.org/c/tactics-and-tropes-of-the-internet-research-agency/

https://disinformationreport.blob.core.windows.net/disinformation-report/NewKnowledge-Disinformation-Report-Slides.pdf

