# Exploring me and my friends' Spotify Music 'Taste Profiles' Using Machine Learning
Using Spotify's SPOTIPY API, I pulled attributes describing thousands of songs that me and 3 other friends had 'favorited' on Spotify, with the goal of comparing our musical tastes using Machine Learning. I used the OneClass Support Vector Machine (OneClassSVM) algorithm from Python's scikit-learn library to visualize each of our music 'taste profiles' based on several song attributes that Spotify provides including:
 - Beats Per Minute (BPM) — The tempo of the song.
 - Energy — The higher the value, the more energetic.
 - Danceability — The higher the value, the more danceable the track
 - Loudness — The higher the value, the louder the song (in dB).
 - Valence (aka positivity) — The higher the value, the more positive the mood.
 - Length — The duration of the song.
 - Acousticness — The higher the value the more acoustic the song
 - Instrumentalness — the higher the value, the fewer the vocals
 - Liveness — higher value indicate the presence of a live audience

The code to extract the songs using the Spotipy API can be found in the Jupyter Notebook files that start with "extract_..."

The code to analyze the songs can be found in the Jupyter Notebook file titled "eda_top_tracks"

Below are some charts comparing 4 individual's Music Tastes. Can you spot which one belongs to a Gen Z? :)

![radar_charts_side_by_side_large_with_legend_cyberpunk_title_colored_right_spaced_white_bg](https://github.com/osirjeremy/spotify_analysis/assets/8055445/d05ca610-23cb-4b3c-9aba-8337b685a71c)

These charts compare the attribute distributions for the 3 individuals' favorite Spotify songs
![Screenshot 2023-10-01 at 11 47 40 AM](https://github.com/osirjeremy/spotify_analysis/assets/8055445/922b4e9a-dae9-4b3f-9b39-b6888440a000)

Finally, this is a visualization of an individual's music taste profile using Principal Component Aanalysis and OneClassSVM algorithms. The orange-shaded area represents the music taste boundary that the algorithm learned. I added labels to show my favorite Taylor Swift songs.
![ml_music_profile_b](https://github.com/osirjeremy/spotify_analysis/assets/8055445/da62598c-1177-4b38-a96a-aca4426fdc3d)



