# Decoding-YouTube-Audiences-Analyzing-Sentiment-Trends-on-Quit-Social-Media-
Sentiment Analysis Project
Overview
This project performs sentiment analysis on a dataset of comments collected from a TEDx talk video on YouTube. The goal is to analyze the sentiment of the comments and uncover insights about viewer reactions to the talk.

Dataset
The dataset contains the following columns:

Name: The name of the commenter
Comment: The text of the comment
Time: The timestamp of the comment
Likes: The number of likes the comment received
Reply Count: The number of replies to the comment
Sentiment: The sentiment of the comment (Positive, Negative, Neutral)
Processed_Comment: The preprocessed version of the comment
Tokenized_Comment: The tokenized version of the comment
Filtered_Comment: The filtered version of the comment
Sentiment_TextBlob: The sentiment of the comment as determined by TextBlob
Tools and Technologies Used
Python
pandas
scikit-learn
matplotlib
seaborn
TextBlob
YouTube Data API
Analysis Results
Distribution of Sentiment Categories:

Positive: 60.5%
Negative: 20.2%
Neutral: 19.3%
Average Likes for Comments by Sentiment:

Positive: 42 likes
Negative: 15 likes
Neutral: 20 likes
Sentiment Variation over Time:

Overall, sentiment tends to be more positive over time, with occasional spikes in negative sentiment.
Sentiment vs. Comment Length:

There is a slight correlation between comment length and sentiment, with longer comments tending to be more positive.
Sentiment vs. Engagement Metrics:

Comments with higher likes and reply counts tend to have more positive sentiment, indicating a correlation between engagement and sentiment.
Conclusion
The sentiment analysis of the TEDx talk comments reveals that the majority of viewers express positive sentiment. Comments with higher engagement metrics, such as likes and reply counts, tend to be more positive. However, there is still a portion of negative and neutral sentiment comments, suggesting a diverse range of opinions among viewers.

Link of Medium Article: https://prateekkaushik22.medium.com/decoding-youtube-audiences-analyzing-sentiment-trends-on-quit-social-media-dr-d31d08765d86
