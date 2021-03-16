# Spotify-Wrapped-2020
Creating my own detailed version of Spotify Wrapped 2020 using my personal streaming history

### Introduction  
I'm a huge music fan, and when Spotify first introduced with their infamous Wrapped feature in 2017, I was happy to discover that there was a way to summarize my listening history throughout the year. The summary lists your top 5 favorite artists as well as your top 5 favorite songs from the year. In addition, Spotify even curates a playlist of 100 songs that you listened to the most, called "Your Top Songs". However, I wanted to develop more detailed insights into my listening history, and I learned that you can access your listening history by requesting Spotify to download your personal data.  

### About the data
Within the zip file, I came across two files regarding my streaming history. The first file, 'StreamingHistory1.csv' consists 10,000 rows of data with columns 'endTime', 'artistName', 'trackName', and 'msPlayed' (milliseconds played). The second file I used was 'StreamingHistory2.csv' and it consisted of the latter 3766 songs that I listened to in 2020. I concatenated these two dataframes into one to make it easier to work with, creating one big dataframe with 13,3766 rows.

### Objectives
While the official Spotify Wrapped tells you your top 100 songs in "Your Top Songs", there's no way of knowing what your favorite artists beyond the top 5. So I attempted to list all of my favorite artists with a few 'groupby' methods. I also sought to find if there were any discrepancies between my custom dataframes and Spotify's Wrapped and created visualizations to depict my listening history throughout the months of 2020. While handling 4 columns was not too troublesome, I know that Spotify's API includes more descriptive characteristics for each song on their platform. These features include: tempo, danceability, valence, etc. In a future project, I hope to find some way to merge these features with my favorite songs and see if there any noticeable patterns or correlations. For example, do I tend to like slower songs, etc.
