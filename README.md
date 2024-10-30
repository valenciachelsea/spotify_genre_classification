In December of 2022, I completed a 10-week Data Science course offered by General Assembly. The purpose of the course was to apply Python packages to Data Science problems. The course required a final presentation, of the student's choosing. My project centered around classifying the genre of songs available on Spotify. 

## Problem
Spotify has millions of songs on their platform. Manually assigning a musical genre to an individual song is not feasible. Song genres are not only used to categorize songs, but also create playlists and recommendations. Predicting the song genre presents an interesting classification problem. This project will review how modeling may be used to help predict the musical genre of a song. 

## Technique
The project aimed to answer the classification using different models, and selecting the model which performed best. The models evaluated we k-nearest neighbors, decision tree, and random forest. Data cleaning and EDA were performed, followed by modeling, and model selection.

## Data Overview
track_id: Unique ID for song (object)

artists: Artist Name(s) (object)
album_name: Album name (object)
track_name: Song name (object)
popularity: Range from 0 to 100, determined by song plays and recency of playing (integer)
duration_ms: Duration of song in milliseconds (integer)
explicit: Does the song contain explicit lyrics? (boolean)
danceability: number between 0 and 1 (float)
energy: number between 0 and 1 (float)
key: number between 0 and 11, represents the 12 keys of music (integer)
loudness: number between -50 and 5 (float)
mode: 0 or 1 (boolean)
speechiness: number between 0 and 1 (float)
acousticness: number between 0 and 1 (float)
instrumentalness: number between 0 and 1 (float)
liveness: number between 0 and 1 (float)
valence: Describes the musical positiveness conveyed by a track, number between 0 and 1 (float)
tempo: number between 0 and 245 (float)
time_signature: number between 1 and 5 (integer)
track_genre: genre of music (object)
track_genre_main: larger bucket for genre of music (object)

