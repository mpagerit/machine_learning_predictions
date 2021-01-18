#  2021 Movie Predictions using a Neural Network
[Visit the project website with original visualizations](https://teamawesome-movies.herokuapp.com/)

This repo is the continuation of the final project of my data analytics certificate. My hypothesis was that the machine learning models could be improved by including fewer years of recent movie data, rathe rthan 40 years of movie data. I ultimately included 10 years of data, 2010-2019. The accuracy of the box office success predictor went up significantly, from 59% to 64.5%. The critical success predictor changed from 61% to 62% accurate.

[Tableau Visualizations of new results](https://public.tableau.com/profile/marianne3066#!/vizhome/ImprovedMoviePredictionNeuralNetwork/MoviePredictionNeuralNetwork)
The new models made different predictions for 2021 than in the original model, predicting 9 movies will be "good", and only 5 movies will be commercial successes.


# Original Project Repo
## Team Members
* John Clark
* Nicole Fejfar
* Jason O'Day
* Marianne Pagerit
	
## Project Summary
* Analyze historical movie data using neural networks to predict future movies' critical and box office success 
	
## Technologies
* Python
	* Beautiful Soup
	* Pandas
	*  Numpy
* Bootstrap & CSS
* Tableau
* scikit-learn
* Flask
*  Heroku
	
## Instructions to run code
*  In Jupyter notebook run 'dataClean.ipynb' first to generate moviesClean.csv. This file was too large to push to repo.
* Run 'Classification Neural Network.ipynb' to generate the models
* If testing code, run the '2021 Prediction Web Scraping.ipynb', however the file this produces is in the repo
* Run '2021 Predictions.ipynb' to generate the predictions
	
## Data Sources
[Historical movie data](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDB-Movie-Data.csv)<br>
[2021 Movie data](https://www.imdb.com/list/ls070080072/)<br>
[Criteria to qualify movie profitibility](https://io9.gizmodo.com/how-much-money-does-a-movie-need-to-make-to-be-profitab-5747305)<br>
[Criteria to qualify critic success](https://www.metacritic.com/about-metascores#:~:text=Metacritic%20designates%20a%20movie%20as,section%20of%20the%20best%20cri)

Original Repo location:
https://github.com/nicolefejfar/Team-Awesome-Final-Project
