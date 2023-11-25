# GNOD Music Recommendation System

## Overview
The GNOD Music Recommendation System is a sophisticated tool that uses data scraping, processing, and machine learning to suggest songs to users based on their preferences. This project is structured in a sequence of steps, each represented by a script that builds upon the work of the previous one.

## Repository Structure
- `Data Collection`
  - `1. Hot Songs List Creation.ipynb`: Collects the top songs from different sources.
- `Data Preprocessing`
  - `2. Spotify Data Collection + Feature Extraction.ipynb`: Uses Spotify's API for accessing playlists and retrieving track IDs and audio features from Spotify.
- `Model Training`
  - `3. Clustering.ipynb`: Scales the features for machine learning and Trains a KMeans clustering model.
- `Application`
  - `4. Song Recommender.ipynb`: The final application script that recommends songs.

## Usage
To run the GNOD Music Recommendation System, follow these steps:
1. Ensure all dependencies are installed from `requirements.txt` (from the "Data" folder).
2. Run the scripts in numerical order, as listed in the repository structure.

## Contributing
Contributions to the GNOD Music Recommendation System are welcome. Please fork the repository, make your changes, and submit a pull request.
