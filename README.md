# Lyric Finder with Spotify and Genius

This project aims to fetch the lyrics of the current song playing on the user's Spotify using Genius.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Python installed on your machine. You can download Python [here](https://www.python.org/downloads/). 

In addition, you will need the following Python libraries:
- os
- sys
- json
- time
- signal
- spotipy
- threading
- webbrowser
- lyricsgenius
- spotipy.util

### Installing

1. Clone the repository
2. Install the requirements
pip install -r requirements.txt

markdown
Copy code

3. Run the Python script
python main.py

markdown
Copy code

### Usage

1. Run the script.
2. The script will fetch the lyrics of the current playing song on Spotify and display them.
3. The script will give options to:
   - Open the Genius URL for the song in a browser.
   - Fetch and display artist info.
   - Continue to the next song.

### Environment Variables

You will need to set the following environment variables:

- `SPOTIPY_CLIENT_ID` - Your Spotify Client ID
- `SPOTIPY_CLIENT_SECRET` - Your Spotify Client Secret
- `SPOTIPY_REDIRECT_URI` - Your Spotify App's Redirect URI
- `GENIUS_ACCESS_TOKEN` - Your Genius Access Token

### Built With

* [Spotipy](https://spotipy.readthedocs.io/en/2.16.1/) - A lightweight Python library for the Spotify Web API
* [LyricsGenius](https://lyricsgenius.readthedocs.io/en/master/) - A simple Python interface for song lyrics from Genius.com
