
![Logo](https://www.begeek.fr/wp-content/uploads/2022/11/Spotify-660x371.jpg.webp)


# Predict the popularity of a new song based on a dataset of 30'000 songs

This study explores a dataset comprising several key variables related to music tracks and playlist characteristics. The dataset offers insights into numerous attributes, including the song's specifics, artist details, playlist information, and various musical features. Below is an overview of the essential columns and their descriptions :


## Variable Descriptions :

- **track_id:** Unique ID for each song.
- **track_name:** Name of the song.
- **track_artist:** Artist(s) associated with the song.
- **track_popularity:** Song popularity score ranging from 0 to 100, where higher scores indicate higher popularity.
- **track_album_id:** Unique ID for the album associated with the song.
- **track_album_name:** Name of the album.
- **track_album_release_date:** Date of the album release.
- **playlist_name:** Name of the playlist.
- **playlist_id:** Unique ID for the playlist.
- **playlist_genre:** Genre of the playlist.
- **playlist_subgenre:** Subgenre of the playlist.
- **danceability:** Describes the suitability of a track for dancing based on various musical elements. Ranges from 0.0 (least danceable) to 1.0 (most danceable).
- **energy:** Represents the intensity and activity of a track, ranging from 0.0 to 1.0.
- **key:** Estimated overall key of the track mapped using standard Pitch Class notation.
- **loudness:** Overall loudness of the track in decibels (dB), with values typically between -60 and 0 dB.
- **mode:** Indicates the modality (major or minor) of the track, represented by 1 for major and 0 for minor.
- **speechiness:** Detects the presence of spoken words in a track, ranging from 0.0 to 1.0.
- **acousticness:** Confidence measure of whether the track is acoustic, ranging from 0.0 to 1.0.
- **instrumentalness:** Predicts whether a track contains no vocals, ranging from 0.0 to 1.0.
- **liveness:** Detects the presence of an audience in the recording, with higher values indicating a higher probability that the track was performed live.
- **valence:** Describes the musical positiveness conveyed by a track, ranging from 0.0 to 1.0.
- **tempo:** Estimated tempo of a track in beats per minute (BPM).
- **duration_ms:** Duration of the song in milliseconds.

This dataset offers a comprehensive perspective on musical attributes, artist details, and playlist characteristics, enabling in-depth analysis and exploration of various music-related trends and patterns.



## Objectives

Our main objective is to explore and analyze in depth the music dataset we have available. Using advanced data analysis techniques, we seek to understand the characteristics that most contribute to a music's popularity.

To do this, we plan to use machine learning methods to create a predictive model. This model should be able, based on various information about a song (such as musical genres, beats, lyrics, etc.), to accurately predict its likely popularity level.

Our end goal is to provide users with a reliable and accurate tool that will allow them to estimate the potential popularity of new music, which would be of great value to artists, record labels and streaming platforms. By leveraging this data intelligently, we hope to provide valuable insights for the music industry and help better understand the factors that influence a song's success.
## This project is implemented in Python and gathers tasks of :
 

- **Data Visualization:**
  - Show correlations between the data and the target on the Jupyter Notebook.

- **Machine Learning Algorithm Modelization:**
  - Implement machine learning algorithms and models on the Jupyter Notebook.

- **Transformation of the Model into a Django API:**
  - Convert the trained machine learning model into an API using Django.

## You will find in this repositery :
 - The PDF version of the PowerPoint presentation.
  - The code in Jupyter notebook format.
  - The Django or Flask API implementation.
