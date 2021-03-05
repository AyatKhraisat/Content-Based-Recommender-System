# Content-Based-Recommender-System

![](https://images.unsplash.com/photo-1598899134739-24c46f58b8c0?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1476&q=80)

Recommendations are playing a major role in social media, advertisement and many other applications. We will start the series with a simple content-based algorithm. You can use it to create similar movies; which are used for 'more like this' or, 'because you watched' and maybe 'recommended for you'.

### What is Content Based Recomendation ?
The content-based Recommender extract movie metadata such as genres, cast, overview, etc. then convert them into features then find similar movies based on these features. 
The content-Based recommender could generate bad results if you didn't utilize metadata wisely, once I got Ice Age as a recommendation because I watched Titanic!. First, you should determine specific criteria of how the recommender system will recommend. Our criteria will be to recommend movies with same features as directors, cast, genres, keywords, release date, etc. The director, genres and cast. Will have a higher weight than the other features.

