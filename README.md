#  2021 Movie Predictions using a Neural Network
[Visit the team website with original analytical results](https://teamawesome-movies.herokuapp.com/)

This is a continuation of the final project for my data analytics certificate. The updates and edits made to this repo since December are my own. Details on the project are below, and you can find the original repo here: https://github.com/nicolefejfar/Team-Awesome-Final-Project

My visualization with updated data is in my Tableau Public profile: [Improved Machine Learning Models](https://public.tableau.com/profile/marianne3066#!/vizhome/ImprovedMoviePredictionNeuralNetwork/MoviePredictionNeuralNetwork)

I made the following changes between the final project and my updated visualization:
* I increased the total number of actors allowed per movie to 10. Limiting to three provided too little data, as there are actors who may be cast in secondary roles who may still be a box-office or critical draw.
* I limited data to 10 years worth of movies, 2010-2019. My hypothesis was that including movies from a larger timeframe reduced our accuracy, as including actors and directors who haven't been active in years likely waters down the impact of current actors and directors.

##Original Project Readme:

**Team Members:**
* Jason O'Day
* John Clark
* Marianne Pagerit
* Nicole Fejfar
	
## Project Summary
Analyze historical movie data using neural networks to predict future movies' critical and box office success 
	
## Technologies
* Python: 
	* Beautiful Soup
	* Pandas
	* Numpy
* Bootstrap & CSS
* Tableau
* scikit-learn
* Flask
* Heroku
	
## Instructions to run code
1. In Jupyter notebook run 'dataClean.ipynb' first to generate moviesClean.csv. This file was too large to push to repo.
1. Run 'Classification Neural Network.ipynb' to generate the models
1. If testing code, run the '2021 Prediction Web Scraping.ipynb', however the file this produces is in the repo
1. Run '2021 Predictions.ipynb' to generate the predictions
	
## Data Sources
[Historical movie data](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDB-Movie-Data.csv)<br>
[2021 Movie data](https://www.imdb.com/list/ls070080072/)<br>
[Criteria to qualify movie profitibility](https://io9.gizmodo.com/how-much-money-does-a-movie-need-to-make-to-be-profitab-5747305)<br>
[Criteria to qualify critic success](https://www.metacritic.com/about-metascores#:~:text=Metacritic%20designates%20a%20movie%20as,section%20of%20the%20best%20cri)

Original Repo location:
https://github.com/nicolefejfar/Team-Awesome-Final-Project
