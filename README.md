# Data Visualization Project

## Data
The data I propose to visualize for my project is a dataset of Spotify's Top 100 songs of 2018. These songs were ecollected using the Spotify Web API and the spotify's Python library. What will the genre's of the songs predict? The following attributes will be evaluated: name, artists, danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms 	time_signature. [The link to the data](https://www.kaggle.com/nadintamer/top-spotify-tracks-of-2018).

## Prototype:
A visualization showing the relationship between danceability and energy . The data shows that relatively high energy and high danceability are important to make hit song. The data also shows very few outliars for this dataset.

[![image](https://user-images.githubusercontent.com/44887761/66723177-08f34d80-ede4-11e9-9ca1-f99034fc947b.png)](https://beta.vizhub.com/samemurk21/6af3bc82208e4a56a695f4b0473640d7)

Are Songs Getting Shorter? Looking into the dataset a bit closer, there seems to be a small restriction in the duration of music, there is only one outlier exceeding over the 6.5-minute mark. Could this change be overly popular in the media to have an average length for music or is a demand from Spotify to use less bandwidth for streaming purposes. The average duration of a track is narrowed down between 2.5 and 4 minutes. These clusters seems to unbiased of genre and danceability but across the board in music.  

[![image](https://user-images.githubusercontent.com/44887761/66865205-bf7e3c00-ef64-11e9-84ea-b30ec73525ba.png)](https://beta.vizhub.com/samemurk21/9bac56d08115406e91f0876c2bd1372d?edit=files&file=index.html)

A visualization showing the relationship between danceability and duration in Milliseconds. 

![image](https://user-images.githubusercontent.com/44887761/67061596-ca84c800-f12e-11e9-9da1-8c79acdd7d82.png)

A visualization showing the relationship between danceability and artists. 

[![image](https://user-images.githubusercontent.com/44887761/66722331-e0665600-edd9-11e9-9e5c-16f7de81644b.png)](https://beta.vizhub.com/samemurk21/6af3bc82208e4a56a695f4b0473640d7)

A visualization showing interactions between key attributes.

[![image](https://user-images.githubusercontent.com/44887761/67542385-9410f500-f6ba-11e9-9ebd-9fa7e607eef7.png)](https://beta.vizhub.com/samemurk21/10d736cbacb64490a6c4b5cbab489ceb?edit=files&file=index.html)
## Questions and Tasks

The following questions are : 

* Are the more popular songs danceable?
  * is there a range of energy for a song to be danceable.

* What do all of these songs have in common?
  * how much similarity and variation are in the data?

* why do people like these songs?
  * What does the majority of the population listen to?


## Sketch:
![image](https://user-images.githubusercontent.com/44887761/66096839-3f220900-e56a-11e9-98e6-eea0e32f7d40.png)

## Open Question
* What does the distribution of the data look like?

* Would the top 100 dataset from 10 years ago correlate well with the current data set?

## Schedule of Deliverables

Danceability of the data:                     Due-10/10/19

Similarity in songs:                          Due-10/3/19

Population interest:                          Due-10/10/19

Trends in musics dataset:                     Due-10/17/19

Summarise Project                             Due-10/24/19


## Definition

Id - Spotify URI of the song

Name - Name of the song

Artists - Artist(s) of the song

Danceability - Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.
energy

Energy - a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.

Key - The key the track is in. Integers map to pitches using standard Pitch Class notation.  

Loudness - The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typical range between -60 and 0 db.

Mode - Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.

Speechiness - Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
Acousticness - A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.

Instrumentalness - Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.

Liveness - Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.

Valence - A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).

Tempo - The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.

Duration_ms - The duration of the track in milliseconds.

Time_signature - An estimated overall time signature of a track. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure).


