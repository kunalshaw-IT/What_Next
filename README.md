# What_Next?
##  A Movie Recommendation System that recommends movies using the K Nearest Neighbours algorithm(KNN) from a list of ~5000 movies

## Dataset
- [IMDB Movie 5000 Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)

## Files
- ***Classifier.py*** is my implementation of the K-Nearest Neighbours algorithm
- ***data.ipynb*** loads the data from the CSV files, cleans it, modifies it into the required format and stores it in JSON files (data preprocessing)
- ***app.py*** is the streamlit app and recommendation engine that runs the KNN algorithm on the data and displays the recommendations
- ***data.json*** and ***titles.json*** are JSON files containg the data created in data.py for faster loading when the recommendation engine is run

## Features

- Options to select movie ( Movie/Content based recommendation )
- Options to select multiple genres ( Genre Based Recommendation )
- Options to select IMDb score
- Options to select number of movies to recommend. ( Range provided is 5 to 30 movies ).
- Recommended Movie Links

## Deployment

The app is deployed on Render at https://what-next.onrender.com/

## Movie based Recommendation
<img width="957" alt="image" src="https://user-images.githubusercontent.com/109387394/211089128-9ece29b7-ebd7-4216-aad7-6169010cacf1.png">

## Genre based Recommendation
<img width="960" alt="image" src="https://user-images.githubusercontent.com/109387394/211090071-a1d0ebf9-e033-4aee-8694-2fc29f6a23db.png">


