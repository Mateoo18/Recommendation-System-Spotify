# 🎧 Spotify Music Recommendation System

This project implements a dynamic, user-adaptive **recommendation system** for Spotify using machine learning techniques. It leverages a dataset of 150,000 songs with rich metadata to suggest personalized tracks based on user preferences and ratings.

## 🚀 Project Overview

- At the start, the user provides musical preferences (genres, artists, or feature values).
- The system recommends a list of tracks that match these preferences.
- After listening to the recommendations on Spotify, the user rates each song from 0 to 5.
- The system uses these ratings to refine future recommendations, learning from the user over time.

The project provides an interactive way to discover new music based on actual feedback rather than static playlists.

## 📁 Dataset

The dataset contains metadata for 150,000 Spotify tracks, with features such as:

- `track_id`: Unique Spotify track identifier  
- `track_name`, `album_name`, `artists`: Basic metadata  
- `popularity`: Spotify popularity score (0–100)  
- `duration_ms`: Track duration in milliseconds  
- `explicit`: Boolean flag for explicit content  
- `danceability`, `energy`, `speechiness`, `acousticness`, `valence`: Audio features (0.0–1.0)  
- `key`, `mode`, `loudness`, `tempo`, `instrumentalness`: Musical descriptors  

## 🧠 Techniques Used

- Content-based filtering
- User feedback integration (ratings from 0 to 5)
- Similarity metrics (e.g., cosine similarity)
- Feature normalization and filtering
- Interactive UI elements (user input → recommendation loop)

## 🛠️ Technologies

- Python (pandas, numpy, scikit-learn)
- Jupyter Notebook
- CSV-based storage (for ratings and metadata)
- Spotify dataset (preloaded)

## ⚠️ Notes

- Ratings are stored and reused to improve recommendation quality over time.

## 🎯 Goal

To create an engaging music discovery experience powered by machine learning — one that learns from the user's input and evolves over time.

## 📬 Author

**Mateusz Nowak**  
Computer Science student & Machine Learning enthusiast

---

