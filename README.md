# Data-Programming---Instagram-Sentiment-Analysis

## Objective 

- How has users’ sentiment of Instagram App Store reviews changed via location?
- We analyze ratings, sentiment, and themes across counties 
- What do users love and hate about the platform?

## Data Set 

- Source: Kaggle - Instagram Ratings and Reviews: Appstore
- 500 rows of data
- Has 11 features
- Represent short-term user sentiment, not year trends 

Note: Since this dataset only captures 500 recent reviews, our analysis focuses on current sentiment, not changes over time

## Cleaning of DataSet

When cleaning the dataset to get the reviews, we had to:

- keep only required columns
- convert date format
- convert score to numeric
- merged title + text into one complete review field
- create time variables

## Sentiment Analysis 

- Sentiment analysis helps us identify whether each review is positive, negative, or neutral, allowing us to understand users’ true feelings beyond star ratings.
- It also helps identify patterns in what users like or dislike, providing deeper insights that ratings alone cannot show.

## Rating Distribution Chart
- Most ratings are 1-star review showing user frustration
 ![Rating Distribution Chart](<Data Programming - Instagram.png>)

## Country Analysis 
- Germany shows the highest level of dissatisfaction
- Both the average star rating and sentiment score for Germany are significantly lower than all   other countries.  
- This suggests that German users may be experiencing more issues or expressing stronger frustration with the app during this period.
![Rating Distribution Chart](<Data Programming - Instagram (2).png>)
![Rating Distribution Chart](<Data Programming - Instagram (3).png>)
  
## Rating vs Sentiment Heatmap 
- 1- star reviews contain both negative and positive wording 
- 5- star reviews are strongly positive 
- Shows that sentiment analysis is needed beyond star ratings
![Rating Distribution Chart](<Data Programming - Instagram (4).png>)

## Limitations

- The dataset contains 500 reviews, which limits statistical generalization
- Reviews are from a short window of time, so they can not be measured over the years 
- Data is from Apple App Store, not Android or other platforms 
- Some languages may affect sentiment scores due to translation challenges

## Conclusion + Recommendations

- sentiment analysis not only illustrates how users feel about the app but also highlights actionable areas for improvement
- Instagram feedback is mixed, with more negative sentiment 
- 1-star ratings are common, showing frustration despite high  engagement
- Instagram's product team to prioritize fixes
optimize feature rollouts
- enhance overall user experience in countries with a low sentiment, like Germany.
- Prioritize fixing bugs and improving stability 
- Improve account recovery and login systems 

