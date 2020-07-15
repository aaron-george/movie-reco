# Movie Recommendation Engine 
Content based recommendation engine to recommend movies based on the movie you liked previously. 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [API](#api)
  * [Installation](#installation)
  * [Run](#run)
  * [To Do](#to-do)
  * [Technologies Used](#technologies-used)

## Demo
[Youtube Link](https://youtu.be/yazbqYvYrTM)

This app is not deployed in any platforms since it uses double the ram provided in the free paas provides like Heroku, AWS, etc.

[![](https://imgur.com/rspSmKB.png)](https://youtu.be/yazbqYvYrTM)

Also check out the  [Medium Blog](https://medium.com/@aaron4george/movie-recommendation-engine-content-based-filtering-ec186e431a04) I have made to understand each functionality of the web app in depth.

## Overview
This is a movie recommendation engine built over 1000 movie dataset vectorising similarity over genre, keywords, directors and cast of the movie. 
The API used in this flask application is https://www.themoviedb.org/documentation/api which provides an extensive dataset of movies wordwide with excellent functionality. 

## API
The API used in this flask application is https://www.themoviedb.org/documentation/api which provides an extensive dataset of movies wordwide with excellent functionality.

To generate API key, make an account in the TMDB and check the API sidebar once your account is approved.

Using the API, we can get a range of functionality for movies and tv shows worldwide including getting recommendatoin itself.

## Technical Aspect
This project is divided into two part:
1. Count Vectorisation/TFIDF Vectorisation - refer blog link 
2. Cosine Similarity-   Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  
 
 
  ![image](https://imgur.com/dw797a6.png)

## Installation
The Code is written in Python 3.8 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Run

1. Install all dependencies in[requirements.txt](https://github.com/aaron-george/movie-reco/blob/master/requirements.txt)
2. Clone/Download this repo
3. replace the api key in /static/recommend.js
4. Run python main.py
5. Go to the local port http://127.0.0.1:5000 in the browser to find the flask app deployed in the local machine 
    

# Sources of the Data

1.[TMDB 10000 dataset](https://www.kaggle.com/afsarjan23/tmdb-movies-dataset)

2.TMDB API data


## To Do
1. Add more movies to the dataset
2. Perform TFIDF Vectorisation/ other methods to find similarity
3. Reduce RAM usage for easy deployment


## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://imgur.com/SaPEgOZ.jpeg" width=200>](https://pandas.pydata.org/) 

[<img target="_blank" src="https://imgur.com/zxi0U1F.jpg" width=270>](https://www.themoviedb.org/documentation/api) 







