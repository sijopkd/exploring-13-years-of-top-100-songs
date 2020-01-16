# Exploring 13 Years of Hot 100 Songs
## *What do the top 100 billboard songs have in common?*

![Image description](hot_100.jpg) <br />

## Task 
Billboard is an American entertainment media brand and is well-known for its music chart Hot100 that is released at the end of every year. This project focuses on analyzing the top 100 songs that were featured in the hot 100 list of the billboard year end list since 2006 till 2018. 

## Approach

1) Data Source:
  - The year end list was scraped from the billboard wesbite
  - For each of the song and artist, the lyrics of each of the songs were scraped from Genius API 
  
2) Data preprocessing
  - Text Cleaning
  - TF-IDF vectorization
  
3) Analysis 
  - Topic modelling using Latent Dirichlet Allocation 
  - Sentimental Analysis 
  - K-Means Clustering 
  - Recommendation System using cosine similarity
  - Engagement (top 25 or not) Prediction using Logistic Regression 

## Results 

- Artists have freedom on choice of topics as they don’t seem to drive position on billboard
- Lyrics are a big indicator of a song making it to Top 25 
- Sentiment distribution does not vary across low and high ranking songs - hinting to the fact that feelings don’t matter as long as the target market is right
- Success is less about the sentiment and topic of the song and more about the total package and the target audience


