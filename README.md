# Exploring my Spotify Music 'Taste Profile' Using Machine Learning
Using the Spotipy API, I pulled my "Top Tracks" from 2017 - 2021 and used the OneClass Support Vector Machine (OneClassSVM) algorithm from Python's scikit-learn library to visualize my music 'taste profile' based on several song attributes that Spotify provides including:
 - Beats Per Minute (BPM) — The tempo of the song.
 - Energy — The higher the value, the more energetic.
 - Danceability — The higher the value, the more danceable the track
 - Loudness — The higher the value, the louder the song (in dB).
 - Valence — The higher the value, the more positive the mood.
 - Length — The duration of the song.
 - Acousticness — The higher the value the more acoustic the song
 - Key — The key the track is in.
 - Instrumentalness — the higher the value, the fewer the vocals
 - Liveness — higher value indicate the presence of a live audience
 - Mode —  indicates the modality (major or minor) of a track

The code to extract the songs using the Spotipy API can be found in the Jupyter Notebook files that start with "extract_..."

The code to analyze the songs can be found in the Jupyter Notebook file titled "analysis_top_tracks"

More info on the Spotipy API can be found here: https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features
