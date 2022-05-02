# Trending-Youtube-Videos-Analysis

## Summary
Trending Youtube Video Statistics: https://www.kaggle.com/datasets/datasnaek/youtube-new?select=CAvideos.csv
The dataset includes popular Youtube video data of different regions over a period of time. 
In this project, I used data for Youtube videos of North America, and try to visualize trends and then create a function of predicting the number of comments to help video creators find gaps between their current videos' performance and trending videos' performance.

## Data Visualization
### 1. Top 30 videos with popular video ids in North America
![alt text](1.png "Title")
Here is the list of the highest-viewing videos. Many videos from the list come from the same id.

### 2. Trending video IDs vs Number of Views
![alt text](2.1.png "Title")
![alt text](2.2.png "Title")
These two bar charts compare the views/likes of these 30 videos versus Video ID. Four outliers are different from the downward trend. The video contents of these four videos are worthy of note.

### 3. What kind of content are the accounts producing?
![alt text](3.png "Title")
Continuing to create videos with a certain category can help the video channel be more popular.

### 4. Correlation Chart
![alt text](4.png "Title")
I selected important numerical variables such as Likes, Comment Counts, Dislikes, Views, and converted category IDs, and checked the correlation between these variables. According to the graph, we can see that these variables are all positively correlated.


## Prediction
![alt text](5.1.png "Title")
### 
In order to help content creators evaluate the performance of their videos, I created a function that predicts comment counts for being a trending video based on other metrics. The creator can compare the real data with the predicted comment count as one of the ways to optimize future video content and user engagement