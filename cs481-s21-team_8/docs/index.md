# Discord Music Bot

## Abstract:
Our project is a Discord bot based around utilizing APIs to rank the musical tastes of users in a Discord chat. It has two parts: a Spotify player inside of Discord, and an analyzer to generate the ranking data.

The first part, the player, stores music played via the bot in an internal buffer. User-linked data is saved, including the YouTube like/dislike radio of the song’s music video and other discographic information. This part of the bot interfaces with Spotify’s API to get the songs to play and then with TheAudioDB to get the user-linked data. 

The second part, the analyzer, takes the like/dislike ratios and uses them to rate musical taste. When called, the bot displays tongue-in-cheek messages to the chat based on the generated rankings. For example, the user with the lowest ratio will be told they need better taste, while the person at the top is called a conformist.

All generated ranking data is stored internally so it can be recalled and displayed to the users with various commands.
We have considered adding push notifications for mobile devices to the bot as well, with a similar tongue-in-cheek style.

## Members:
 - Sean Mullarkey
 - Forrest Burt
 - Ben Harper

## Project Demo:
[Watch the demo on YouTube!](https://www.youtube.com/watch?v=nRVmrKPQnYY&ab_channel=BenHarper)

## Screenshots
![leadboard](mbleaderboard.png)
![recently played](mbsonglist.png)
![now playing](mbnowplaying.png)
![search results](mbsearch.png)
![search by album](mbalbumsearch.png)
![search by artist](mbartistsearch.png)
