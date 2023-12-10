# Predictive Cinematics: A Model for Forecasting Movie Ratings

## Authors: Lauri Leppik, Jan Erik Köst, Kaur Veere

The movie industry is a multi-billion dollar industry with a rich history and a wide range of products. Understanding the factors that contribute to movie ratings and popularity can provide valuable insights for filmmakers, distributors, and marketers. During this project we attempted to find information valuable to said end-users. We used a dataset from kaggle which contains information about around 1,000,000 movies and their features (such as average rating, revenue, popularity, description) kaggle link: https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies 

### NOTE! THE ORIGINAL DATASET IS NEEDED FOR RUNNING Cleaning_Data.ipynb. THE ORIGINAL DATASET IS NOT PROVIDED IN THIS REPOSITORY DUE TO IT BEING TOO LARGE, OTHER NOTEBOOKS CAN BE ACCESSED WITHOUT SAID DATASET AS SMALLER (AND CLEANER) DATASETS ARE PRESENT IN THIS REPOSITORY! 

Goals:

1)Develop a predictive model that can estimate movie ratings.
2)Analyze trends in movie popularity over the years
3)Analyze the movie descriptions to identify common themes, keywords, or phrases that may impact movie ratings.

Notebook used solely for cleaning data purposes. Not necessary since the results of this notebook are .csv files listed below.
Cleaning_Data.ipynb

Notebooks for each 3 of our goals:

1)
Predict_movie_ratings.ipynb

2)
Popularity_Through_Years.ipynb

3)
Examine_Ratings_Description.ipynb

PDF that contains detailed information about our project:

H13_report.pdf

2 Results files for cleaning the data. 1 has movies with less than 10k revenue and budget removed from the dataset and other has them replaced with median values of the other entries:

fil_data_movies_lessthan10k_removed.csv

fil_data_movies_lessthan10k_replaced.csv

### Using the repository: 
Necessary libraries: pandas, matplotlib, sklearn, math, numpy, WordCloud, nltk, gensim, TextBlob

Other than that download the original dataset from: https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies and for each of the goals a different notebook is provided that can be opened with for example Jupyter Notebook or VSCode.
