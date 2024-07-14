# Spotify and Youtube Exploratory Data Analysis(EDA)
EDA is a data analysis method used to better understand a dataset and discover significant features, patterns, and relationships within it. The primary purpose of EDA is to gain more information about the dataset and to prepare for future analyses. 

## About Dataset
It is a dataset consisting of songs by various artists worldwide, and for each song, the following are provided: various statistics of the music release on Spotify, including the number of streams; the view count of the official music video of the song on YouTube.

## About Data Columns
Track: The name of the song as it appears on the Spotify platform.
Artist: The name of the artist.
Url_spotify: The URL of the artist on Spotify.
Album: The album in which the song is included on Spotify.
Album_type: Indicates whether the song is released as a single or as part of an album on Spotify.
Uri: A Spotify link used to find the song via the Spotify API.
Danceability: Describes the suitability of the song for dancing. 0.0 is the least danceable, while 1.0 is the most danceable.
Energy: A measure from 0.0 to 1.0 representing the perceived intensity and activity of the song.
Key: Represents the key of the song. Integers map notes using the standard Pitch Class notation. For example, 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key is detected, the value is -1.
Loudness: A measure of the overall loudness of the song (decibels - dB). Typically ranges from -60 to 0 dB.
Speechiness: Detects the presence of speech-like sounds in the song. The closer the value is to 1.0, the more speech-like the recording is.
Acousticness: A confidence measure from 0.0 to 1.0 of how acoustic the song is. 1.0 represents high confidence that the track is acoustic.
Instrumentalness: Predicts whether the song contains vocals. The closer the value is to 1.0, the greater likelihood that the track does not contain vocals.
Liveness: Detects the presence of an audience in the recording. Higher liveness values indicate a higher likelihood of the song being performed live.
Valence: A measure from 0.0 to 1.0 describing the musical positiveness of the song. High valence indicates positive musical feelings, while low valence indicates negative musical feelings.
Tempo: The estimated tempo (beats per minute - BPM) of the song.
Duration_ms: The duration of the song measured in milliseconds.
Stream: The number of streams the song has on Spotify.
Url_youtube: The URL of the associated YouTube video, if any.
Title: The title of the YouTube music video.
Channel: The name of the channel that published the video.
Views: The number of views of the video on YouTube.
Likes: The number of likes on the video on YouTube.
Comments: The number of comments on the video on YouTube.
Description: The description of the video on YouTube.
Licensed: Indicates whether the video represents licensed content.
official_video: A boolean value indicating whether the song is an official video.



