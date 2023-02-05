# Twitter Sentiment Analysis using Kafka, Spark Streaming and Elastic Search
**Introduction**: 
Sentiment analysis helps companies to analyze tweets to know how customers are talking about their products and services. Getting insights to drive business decision, identifying issues in the product etc.

Sentiment analysis uses machine learning to identify people's view on certain topic. Whether it is negative, positive or neutral.

Advantages of Twitter analysis:
- Analysis of tweets in real-time 24/7.
- Do it at scale and analyze thousands of tweets in seconds.
- And more importantly, get the insights whenever we want.


Here in this project, I am presenting a program to analyze continuous real-time tweets to know how people are talking about any specific topic or hashtag.
<br>
Skills Used: Machine Learning, Kafka, Spark, Elastic Search.



## About running the project: 
1. This project has two python files, Scraper and Analyzer. Scraper gathers the tweets using Twitter API. And Analyzer performs the classification on the tweets using Naive Bayes model.
2. For running these python files we need to install Kafka, Zookeeper and Elastic Search in the local computer.(Please refer to official websites to download, install and run the servers)
3. When all the servers are up. Install all dependencies of the python files and run the python files.
4. For viewing the tweet classification charts, go to ElasticSearch dashboard and generate visualizations. 
5. Visualizations should look like the following images.
<img width="400" alt="Screenshot 2023-02-05 at 1 13 18 PM" src="https://user-images.githubusercontent.com/26655938/216839894-c866e15b-19e6-42e9-a255-691932c9aaf9.png">
<img width="400" alt="Screenshot 2023-02-05 at 1 13 30 PM" src="https://user-images.githubusercontent.com/26655938/216839906-f1d086ce-b18e-4cd0-a706-67098091a228.png">
6. Visualizations will change in realtime as we keep on getting new tweets.



### References: 
- https://github.com/Ashwanikumarkashyap/sentiment-analysis-of-streaming-tweets-and-visualizations-using-its-kafka-kibana#readme
- https://huggingface.co/blog/sentiment-analysis-twitter
