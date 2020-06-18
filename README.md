#Twitter Sentiment Analysis using UiPath
In this process, I am analysing top 20 tweets which contains popular hashtag #ThursdayThoughts and then trying to predict if the tweet is having a positive or negative sentiment.
I am using Data Scraping to grab top 20 tweets and then looping those tweets through For Each Row loop.
I am using HTTP Request activity from UiPath.Web.Activities package to do an HTTP POST request to "http://text-processing.com/api/sentiment/" containing the tweet I want to analyse. And then, I used Deserialize JSON activity to convert JSON string to JObject.
I analysed the probablity of tweet being positive, negative or neutral and then saved details in an excel file.
