# Data Science Project - Recommender System (Netflix)

Here is my take on the dataset contructed from Netflix which begun in October 2006.
\
**Objective:** _<0.9525_ RMSE score (Root Mean Square Error) 

## Codes and Resources Used 
**Python Version:** 3.8 \
**Packages:** numpy, pandas, matplotlib, wordcloud, sklearn, surprise, tensorflow \
**Dataset from Kaggle:** https://www.kaggle.com/netflix-inc/netflix-prize-data \
**Prize Details:** http://www.netflixprize.com 

## Data Overview 
Dataset was contructed to support the participants in the Netflix Prize. 

- Netflix Customers: 480,000 (randomly chosen and annoymous) 
- Movie Titles: 17,000 
- Data collected from: Oct 1998 to Dec 2005 
- Ratings: 1 to 5 stars
- Date of Rating 
- Movie ID
- Movie's Year of Release

Due to the nature of the data provided, collaborative filtering was used in the process. Thereafter, top 3 models were used to recommend the targeted user the next 10 movies to watch. 
\
<img width="400" alt="Netflix Process Overview" src="https://user-images.githubusercontent.com/77626155/128596852-21fe5932-e81d-4cee-9e90-41507dac9c0d.PNG">

## Model Building
Due to some restraints, I have reduced the data size from 100million to 5 million. The 5 million data comes from Jun to Dec 2005 since 50% of the data were rated in 2005.
\
<img width="300" alt="Rating Distribution 1999 to 2005" src="https://user-images.githubusercontent.com/77626155/128596727-82a16ea8-f5ce-4452-9faf-c59d101cc149.PNG">
<img width="290" alt="Rating Distribution 2005" src="https://user-images.githubusercontent.com/77626155/128596737-7befcc9f-54f5-44ca-925c-d5ceb9310cd5.PNG">

Root Mean Square Error (RMSE) was one of the metrics used to evaluate the project. 

<img width="600" alt="Netflix RMSE Overview (tabular format)" src="https://user-images.githubusercontent.com/77626155/128596596-706a850f-f293-4366-8423-ab8dfac5329c.PNG">


## Recommendations
Recommendations were provided using collaborative filtering with models via user. 


## Takeaways 
Over the span of 10 days, whilst working as a full-timer, I am glad to attain such great results. I believe with better device and more time given prior to the presentation, I could have better results. As most of my time spent was running the different models with different data size. At the same time, trying to figure out how do I not lose accuracy with less data (from the original dataset provided). 
