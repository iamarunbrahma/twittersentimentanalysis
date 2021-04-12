# Twitter Sentiment Analysis using UiPath

In this process, I am analysing top 20 tweets which contains popular hashtag [#ThursdayThoughts](https://twitter.com/search?q=%23ThursdayThoughts) and then trying to predict if the tweet is having a positive or negative sentiment.

I am using HTTP Request activity from UiPath.Web.Activities package to do an HTTP POST request to [Text Processing Sentiment API](http://text-processing.com/api/sentiment) containing the tweet I want to analyse. After that, I used Deserialize JSON activity to convert JSON string to JObject.

I analysed the probablity of tweet being positive, negative or neutral and then saved details in an excel file.
