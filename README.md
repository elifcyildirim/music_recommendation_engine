![music_recommendation.jpeg](images/music_recommendation.jpeg)

# Coolest music recommendation engine out there!

I built a music recommender using an unsupervised machine learning technique. Simply run the **3_Clustering_and_the_song_recommender.ipynb** file and input your favorite songs as prompted. The recommender will give out equally cool music suggestions for you to enjoy. Do not pass on without trying -you'll be surprised at the taste of this engine!

## Data

- 200 top songs scraped from https://playback.fm and https://www.popvortex.com
- Over 16000 songs that are retrieved using the Spotify API

## Developer instructions

### Files included
   
- **1_Scraping_the_music_websites.ipynb.** This notebook scrapes two different websites to achieve a dataframe of top 200 songs.
- **2_Spotify_API.ipynb.** In this notebook, I use the spotify API to scrape data from multiple spotify playlists. By doing this, I create a dataframe of Over 16000 songs.
- **3_Clustering_and_the_song_recommender.ipynb.** You can run this notebook to enjoy your song recommendations.

## Tools

- Jupyter notebook 6.4.8.
- Web Scraping (bs4)
- Spotify API
- Numpy, pandas, scikit-learn
