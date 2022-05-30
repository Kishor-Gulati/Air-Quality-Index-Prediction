# Air-Quality-Index-Prediction
Got the idea from a youtuber.
Using a python code, I web scrapped data, collected and downloaded weather data as HTML pages from tutiempo.com.
Using another python code, I extrated the required data from HTML pages and saved them in tables(as csv files)
I cleaned and sorted data by joining data sets and then, drew basic insights to understand the impact of independent features on the dependant featues.
Applied various regression models and trained them using the new combined data and drew graphs to check the efficiency of the models.
Compared all models and chose random forest regression model on basis of Mean Absolute Error, Mean Squared Error and Root Mean Squared Error.
Used Flask to run an API(with POST method), to display the final predictions on a browser.
