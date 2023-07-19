#Lyric Finder with Spotify and Genius
This project aims to fetch the lyrics of the current song playing on the user's Spotify using Genius.

#Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#Prerequisites
You need to have Python installed on your machine. You can download Python here.

In addition, you will need the following Python libraries:

os
sys
json
time
signal
spotipy
threading
webbrowser
lyricsgenius
spotipy.util
##Installing
Clone the repository
bash
Copy code
git clone https://github.com/your_username/your_repository.git
Install the requirements
Copy code
pip install -r requirements.txt
Run the Python script
css
Copy code
python main.py
Usage
Run the script.
The script will fetch the lyrics of the current playing song on Spotify and display them.
The script will give options to:
Open the Genius URL for the song in a browser.
Fetch and display artist info.
Continue to the next song.
Environment Variables
You will need to set the following environment variables:

SPOTIPY_CLIENT_ID - Your Spotify Client ID
SPOTIPY_CLIENT_SECRET - Your Spotify Client Secret
SPOTIPY_REDIRECT_URI - Your Spotify App's Redirect URI
GENIUS_ACCESS_TOKEN - Your Genius Access Token
Built With
Spotipy - A lightweight Python library for the Spotify Web API
LyricsGenius - A simple Python interface for song lyrics from Genius.com
