# The Askeladden Algorithm 

W207 | Applied Machine Learning | Spring 2019
Team Troll Trappers: Laura Pintos, Ramiro Cadavid, and Anna Jacobson

## Introduction

In February 2019, as part of special counsel Robert Mueller’s investigation of the Russian government's efforts to interfere in the 2016 presidential election, the United States Department of Justice charged 13 Russian nationals with illegally meddling in American political processes. The defendants worked for a well-funded “troll factory” called the Internet Research Agency (IRA), which reportedly had 400 employees, or “trolls”, working 12-hour shifts from a nondescript business center in St. Petersburg. The IRA ran a sophisticated, coordinated campaign to spread disinformation and sow discord into American politics via social media, often Twitter.

Twitter has identified and suspended thousands of these malicious accounts, deleting millions of the trolls’ tweets from public view on the platform. While other news outlets have published samples, it has been difficult to understand the full scale and scope of the IRA’s efforts, as well as the details of its strategy and tactics. According to Alina Polyakova, a foreign policy fellow at the Brookings Institution, “Wiping the content doesn’t wipe out the damage caused, and it prevents us from learning about how to be better prepared for such attacks in the future.” To address this problem, and “in line with our principles of transparency and to improve public understanding of alleged foreign influence campaigns,” Twitter has now made publicly available archives of Tweets and media that it believes resulted from potentially state-backed information operations.

More than 20% of the English-language troll tweets came from accounts with user names that mimicked those of legitimate news outlets. The purpose of this project is to try to predict "fake news" troll tweets.

## Repo Contents

### 1. W207 Final Project - The Askeladden Algorithm.ipynb
This is the main notebook for the project.

### 2. W207 Final Project - Initial Dataset Creation.ipynb
This notebook includes the processing of the two original dataset (troll tweets and real news tweets) into the combined dataset used in the main notebook.

### 3. W207 Final Project - Production Pipeline.ipynb
This notebook includes the production pipeline for parameter optimization using GridSearchCV.

### 4. W207 Final Project - Presentation.pdf
Slide deck from in-class presentation of project.

### 5. Data
    a. ira_tweets_english.csv - The troll dataset, used in the Initial Dataset Creation notebook.    
    b. real_news_wfox.csv - The real news dataset, used in the Initial Dataset Creation notebook.  
    c. news_tweets_big.csv - The combined real/troll news dataset, used in the main notebook.
    Note that the original troll tweet dataset published by Twitter is not included in this repo due to size limitations.
