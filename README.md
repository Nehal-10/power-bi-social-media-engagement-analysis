Social Media Engagement Analysis

Introduction to Power BI:
Microsoft Power BI is a powerful business intelligence tool that transforms complex data into interactive visual reports. It connects to multiple sources, simplifies modelling, and delivers real-time insights through intuitive dashboards. Power BI empowers users to analyse trends, monitor performance, and support data-driven decisions with visually engaging, easy-to-understand analytics. Report was created using Microsoft Power BI Desktop Version: 2.144.878.0 64-bit (June, 2025).

About Data:
The dataset was sourced from Kaggle. It consists of social media post-level data containing 24 columns and approximately 12,000 records (sample shown). It primarily consists of Social Media Analytics Domain. It includes detailed information about posts such as platform, timing, location, hashtags, sentiment, user engagement metrics, and campaign attributes.
Dataset Link: https://www.kaggle.com/datasets/subashmaster0411/social-media-engagement-dataset 

Dimensions:
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

Measures:
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

Problem Statement:
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
