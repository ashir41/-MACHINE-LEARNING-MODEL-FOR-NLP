Social media sites like Twitter, which provide real-time insights into popular attitudes, trends,
 and sentiments, have become information goldmines in the digital age. Sentiment analysis of
 tweets has become essential for a variety of applications, from political analysis to brand
 monitoring. Because machine learning is scalable and successful in this context, it has attracted a
 lot of attention to be used for sentiment analysis.This project explores the use of machine
 learning algorithms for sentiment analysis on Twitter. To be more precise, we use three different
 models to categorize tweets into positive and negative sentiments: decision trees, linear
 regression, and Naive Bayes. The goal is to use these algorithms' power to reliably identify the
 underlying sentiment of tweets and deliver insightful information to a range of stakeholders.The
 accuracy, F1 score, precision, recall, and other important metrics are used to assess the models'
 performance. These metrics provide a thorough understanding of how well the models identify
 tweets accurately and reduce misclassifications. We seek to evaluate each model's robustness
 and dependability in identifying the subtleties of sentiment conveyed in tweets by looking at
 these measures.In addition, this project involves a performance comparison of the three models.
 Weseek to determine the advantages and disadvantages of each model in the context of Twitter
 sentiment analysis by contrasting their accuracy ratings and other assessment criteria. A
 comparison like this helps to explain which models are appropriate for real-world use and sheds
 light on how well each model performs in various scenarios and datasets. This study is
 essentially a methodical investigation of Twitter sentiment analysis using a machine learning
 perspective. Through the application of advanced algorithms and rigorous evaluation methods,
 we want to decipher the complex web of emotions contained in tweets and open up new avenues
 for better informed decision-making across many industries.
 Dataset description
 Source
 we've downloaded it in a formatted way from Kaggle.
 Link: https://www.kaggle.com/datasets/kazanova/sentiment140
 Data Description
 This dataset is known as sentiment140, comprising 1,600,000 tweets gathered through the
 Twitter API. Each tweet is annotated with a polarity value indicating sentiment (0 for negative, 2
 for neutral, and 4 for positive), making it suitable for sentiment detection tasks. The dataset
 consists of six fields:
 
 1. Target: Indicates the polarity of the tweet (0 for negative, 2 for neutral, 4 for positive).
 2. IDs: Represents the tweet's unique identifier (e.g., 2087).
 3. Date: Records the date and time of the tweet's creation (e.g., Sat May 16 23:58:44 UTC
 2009).
 4. Flag: Denotes the query used to extract the tweet; if absent, the value is recorded as
 NO_QUERY.
 5. User: Specifies the username of the tweet's author (e.g., robotickilldozr).
 6. Text: Contains the actual text content of the tweet (e.g., "Lyx is cool").
 For further details on the dataset's creation process and associated resources, the official link is
 provided. Additionally, there is an official paper detailing the methodology employed.
 The creators of the dataset explain their unique approach, which involved automatically
 generating training data rather than relying on manual annotation by humans. Their method
 considered tweets containing positive emoticons (like :) ) as positive and those with negative
 emoticons (like :( ) as negative. They utilized the Twitter Search API and employed keyword
 searches to collect the tweets
