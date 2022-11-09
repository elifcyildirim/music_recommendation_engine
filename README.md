![music_recommendation.jpeg](images/music_recommendation.jpeg)

# Coolest music recommendation engine out there!

In this project, I levereged machine learning to built a music recommender. In **3_Clustering_and_the_song_recommender.ipynb**, the user is prompted to input one of their favorite songs. Upon this input, the recommender will employ a clustering algorithm to give out an equally cool music suggestion for the user to enjoy.

## Data

- 200 top songs scraped from https://playback.fm and https://www.popvortex.com
- Over 16000 songs that are retrieved using the Spotify API

## Files included
   
- **1_Scraping_the_music_websites.ipynb.** This notebook scrapes two different websites to achieve a dataframe of top 200 songs.
- **2_Spotify_API.ipynb.** In this notebook, I use the spotify API to scrape data from multiple spotify playlists. By doing this, I create a dataframe of Over 16000 songs.
- **3_Clustering_and_the_song_recommender.ipynb.** You can run this notebook to enjoy some tasteful music recommendations.

## Tools

- Jupyter notebook 6.4.8.
- Web Scraping (bs4)
- Spotify API
- Numpy, pandas, scikit-learn
