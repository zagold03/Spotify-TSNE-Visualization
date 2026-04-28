# Spotify-TSNE-Visualization
This was part of a Topological Data Analysis Project: Interactive t-SNE visualization of Spotify tracks that clusters songs by audio features and lets users explore music “vibes” with clickable playback through Spotify embeds.
This project builds an interactive visualization of Spotify tracks using t-SNE and clustering techniques. Songs are grouped based on audio features (e.g., energy, danceability, tempo), allowing you to explore patterns and “vibes” in music.

An interactive plot lets you click on songs to view details and play them directly via Spotify.
###  How to Run

1. Open the notebook (`.ipynb` file).
2. Run all cells **from top to bottom**.
3. When prompted:
   - Create a developer account at the Spotify Developer Dashboard
   - Generate your **Client ID** and **Client Secret**
   - Paste them into the notebook where indicated

---

###  What It Does

- Loads and preprocesses Spotify track data  
- Applies **t-SNE** for dimensionality reduction  
- Uses **KMeans clustering** to group similar songs  
- Visualizes clusters in 2D space  
- Provides an **interactive plot** where you can:
  - Click on a point  
  - View song name and artist  
  - Play the track via Spotify embed  

---

###  Notes

- Simply run the notebook sequentially—no additional setup required  
- Internet connection is required for Spotify playback  
- Interactive components may take a few seconds to load  

---

###  Goal

To explore how music clusters based on audio characteristics rather than genre, helping uncover hidden patterns and “vibes” across songs.
