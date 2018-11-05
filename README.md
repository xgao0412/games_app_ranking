# games_app_ranking

This webpage is showing the top hottest games in twitter for the past week. Users can see the on-trend games, and also notice the games that are not popular anymore. I used twitterscraper library to query the games app names, which is obtained by scraping the itune games webpages. Then I store the information like number of replies, retweets for each tweet and combine them for each game. The rankings are based on the summation of number of replies, retweets and other measurements. The last column shows a website that detects the fake reviews for that games. 

Then a static website is deployed by using php, flask and heroku.

You can find the [website](https://games-app-hotness.herokuapp.com/index.html). It shows DomiNations is the most hottest games in Twitter for that week
