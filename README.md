# Social Media Engagement Analysis

## Introduction to Power BI:
Microsoft Power BI is a powerful business intelligence tool that transforms complex data into interactive visual reports. It connects to multiple sources, simplifies modelling, and delivers real-time insights through intuitive dashboards. Power BI empowers users to analyse trends, monitor performance, and support data-driven decisions with visually engaging, easy-to-understand analytics. Report was created using Microsoft Power BI Desktop Version: 2.144.878.0 64-bit (June, 2025).

## About Data:
The dataset was sourced from Kaggle. It consists of social media post-level data containing 24 columns and approximately 12,000 records (sample shown). It primarily consists of Social Media Analytics Domain. It includes detailed information about posts such as platform, timing, location, hashtags, sentiment, user engagement metrics, and campaign attributes.
Dataset Link: https://www.kaggle.com/datasets/subashmaster0411/social-media-engagement-dataset 

## Dimensions:
1.	post_id – Unique identifier for each post
2.	timestamp – Date and time when the post was published
3.	day_of_week – Day on which the post was made
4.	platform – The social media platform (e.g., Twitter, Reddit, Instagram)
5.	location – Geographical location (city, country) of the post
6.	hashtags – Hashtags used in the post
7.	keywords – Extracted keywords from the post content
8.	topic_category – Topic type (e.g., Pricing, Delivery, Support)
9.	sentiment_label – Sentiment classification (Positive, Negative, Neutral)
10.	emotion_type – Emotion expressed in the post (e.g., Excited, Angry, Sad)
11.	brand_name – Brand being mentioned or discussed
12.	product_name – Specific product being referred to
13.	campaign_name – Marketing or product campaign name
14.	campaign_phase – Phase of the campaign (Launch, Post-Launch, etc.)

## Measures:
1.	sentiment_score – Numeric score indicating sentiment polarity
2.	toxicity_score – Numeric score indicating toxicity level of the post
3.	likes_count – Number of likes received
4.	shares_count – Number of shares or retweets
5.	comments_count – Number of comments on the post
6.	impressions – Number of views or reach of the post
7.	engagement_rate – Engagement ratio (based on likes, shares, comments vs. impressions)
8.	user_past_sentiment_avg – User’s historical average sentiment score
9.	user_engagement_growth – Change in engagement compared to previous posts
10.	buzz_change_rate – Rate of change in overall visibility or buzz for the post

## Problem Statement:
1.	Engagement Rate by Date
2.	Total Post By Date
3.	Engagement Rate by Campaign
4.	Maximum Engagement Rate By Day of Posting
5.	Maximum Engagement Rate By Day of Platform
6.	Average Engagement % By Emotion
7.	Average Engagement rate and Average User past sentiment By Brand Name
8.	Average Sentiment Score by Topic Category
9.	Average Engagement By Sentiments
10.	Top Brands Having Toxicity Score
11.	Average Engagement % By Sentiment Shift
12.	Total User Engagement Growth By Campaign Phase
13.	Total of User Past Sentiment by Emotion Type
14.	Total User Engagement Growth By Emotion Type
15.	Average Engagement Rate by Country
16.	Total Impression By Country
17.	Average Sentiment Score By Hashtags
18.	Average Sentiment Score By Keywords

## Insights:
1.	Posting activity is fairly consistent across months. May and December have slightly higher posting activity, while February saw the lowest.
2.	Data suggests that engagement peaks during the start and end of the year.
3.	The campaign “SummerDreams" had the highest engagement. Campaigns like “BackToschool” and “SustainableFuture” had the lowest engagement.
4.	Data shows Wednesday had the highest engagement rate among days of the week.
5.	Reddit had the highest engagement rate among platforms at 26%.Instagram followed closely with 25% engagement.
6.	The most common emotions associated with higher engagement are “Excited” and “Sad” both at 21%.
7.	Microsoft has the highest average engagement rate among the listed brands. Coca-Cola has the lowest user sentiment average among all brands.
8.	The topic “Delivery” has the highest average sentiment score. “Product” receives the lowest sentiment score, indicating dissatisfaction. The topic "Product" had fewer improvements compared to others.
9.	Negative sentiment posts perform better in engagement than positive ones.
10.	41% of emotions contributed to significantly improved engagement. Another 41% of emotions led to significantly declined engagement. Only 19% of emotions resulted in stable engagement levels
11.	Post-launch campaigns saw the highest growth in user engagement.
12.	“Angry” emotions were associated with a decline in engagement growth.
13.	At 298.96, USA had the highest Sum of engagement rate and was 293.19% higher than Nigeria, which had the lowest Sum of engagement rate at 76.03.
14.	Engagement is highest in tech-dominant or digitally active markets, such as the USA, India, and South Korea.
15.	High Impressions and High Sentiment — impression-rich countries like USA and India should still monitor their sentiment scores.
16.	The USA alone accounts for over 12% of total impressions, making it the most significant market by a large margin.
17.	High-usage hashtags like #Fitness, #Reviews, and #BestValue show strong content alignment with themes of health, evaluation, and affordability.
18.	Keywords emphasize speed, affordability, and customer support — these are central to campaign messaging.
