# TwitterEtl
Twitter Sentiment Analysis
We used python Library Tweepy for extracting twitter tweets for particular topic say '@elonmusk' later it was reformated and appended in List. This List of dictionary was later converted into dataframe which was then transformed into csv file.
All above code was automated using Airflow DAG which was hosted on AWS EC2 instance.
