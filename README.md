# Prodigy_Infotech_Internship_Task_4
Analyzing and Visualizing sentiment patterns in social media data (Twitter) to understand public opinion and attitude towards specific topics or brands.

**Twitter Sentiment Analysis **
This project focuses on analyzing and visualizing sentiment patterns in social media data to understand public opinion and attitude towards specific topics or brands. The analysis was performed on Twitter sentiment data, consisting of both training and validation datasets.

**Data Preparation:**
The datasets twitter_training.csv and twitter_validation.csv were loaded and combined into a single DataFrame for comprehensive analysis.
Column names were manually assigned as: ['tweet_id', 'entity', 'sentiment', 'content'].
Missing values were identified and removed to ensure clean and consistent data.
A new column was added with cleaned text, stripping out URLs, mentions, punctuation, and converting all text to lowercase for analysis.

**Visualizations and Analysis:**
Countplot for Sentiment Distribution:
A bar chart was plotted to show the distribution of sentiments (Positive, Negative, Neutral) across all tweets, providing an overview of general sentiment patterns in the dataset.

Countplot for Sentiment Distribution by Top 10 Entities:
The top 10 most mentioned entities were identified, and their sentiment breakdowns were visualized using a grouped countplot, highlighting which entities receive more positive or negative attention.

Word Clouds for Positive and Negative Tweets:
Separate word clouds were generated for positive and negative tweets to visually explore commonly used words in each sentiment category.

Interactive Sentiment Breakdown by Brand:
An interactive bar chart was created using Plotly to compare the top 10 most frequent words in positive vs negative tweets, offering deeper insight into the language associated with each sentiment.

Pie Chart of Sentiment Proportions:
A pie chart visualized the overall sentiment proportions in the dataset, showing what fraction of tweets fall under each sentiment class.

Entity Sentiment Score Plot:
A sentiment score was computed for each entity by mapping sentiments to numerical values (Positive = 1, Neutral = 0, Negative = -1). A bar chart plotted the average sentiment score per entity, providing a metric to gauge public opinion about each brand or topic.

**Conclusion:**
Through this analysis, we were able to extract meaningful insights into public sentiment toward various entities based on Twitter data. The sentiment distribution shows the overall emotional tone present in user tweets, while the entity-specific analysis reveals which topics or brands are perceived positively or negatively. Word clouds and keyword frequency analyses help identify the language patterns associated with each sentiment, providing useful cues for sentiment drivers.
This approach demonstrates how social media data can be leveraged to monitor public opinion at scale. Such insights can be valuable for brand management, marketing strategy, and public relations by helping stakeholders understand how their brand or topic is being discussed and perceived online.
