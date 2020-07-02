# Spotify-Audio-Analysis
The purpose of this project is to analyze the music that different artists on Spotify produce. 
For this analysis, I have made a list of top 50 artists from a wide range of genres. 
For the study, I will access the Spotify Web API, which provides data from the Spotify music catalog. This can be accessed via standard HTTPS requests to an API endpoint. 
The Spotify API among other things, provide audio statistics and features such as danceability, valence and tempo for each track. Each feature measures an aspect of a song.

With the help of Spotipy for Python, I induvidually searched for each artist in my list, extracted the unique URI of the "This Is" playlist. With each ID, I obtained a list of all the tracks in the playlist and extracted the audio features for each track using the Spotify API methods. 
Now, after extracting the features for each track, I calculated their mean to get a summary for each artist. 
This mean summary of all features was saved to a csv. 
This was then used to do an Exploratory Data Analysis with Pandas, Matplotlib and Seaborn in a Jupyter Notebook.
