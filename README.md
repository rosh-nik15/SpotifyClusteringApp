# 🎧 Spotify Music Recommendation System

## 🚀 Project Overview
An unsupervised machine learning project that groups Spotify songs into clusters based on their audio features and recommends similar songs.

The system analyzes musical attributes like danceability, energy, tempo, valence, loudness, and acousticness to detect patterns in songs and group them into natural clusters of similar music styles.


---

## 🎯 Goal

- To build a system that recommends songs by clustering them based on their audio features using machine learning algorithms.
- This project demonstrates:
Machine Learning Pipeline Development
Feature Engineering for Audio Data
Unsupervised Learning Algorithms
Model Evaluation
Interactive ML Deployment

---

## 📊 Dataset

- **Name:** Spotify Songs Dataset  
- **Source:** Contains audio features such as danceability, energy, tempo, acousticness, valence, etc., for a large number of songs.

## ⚙️ Machine Learning Pipeline

The project follows a complete ML pipeline:

1. **Data Cleaning**
   - Removing missing values
   - Selecting relevant Spotify audio features

2. **Feature Scaling**
   - Standardization using **StandardScaler**
   - Ensures all features contribute equally to clustering and prevents scale bias

3. **Dimensionality Reduction (Optional)**
   - Used for visualization of high-dimensional feature space
   - Techniques include:
     - **PCA (Principal Component Analysis)**
     - **t-SNE (t-Distributed Stochastic Neighbor Embedding)**

---

## 🧠 Algorithms Used

- **K-Means Clustering**
  - Partitions songs into *K clusters* based on feature similarity
  - Efficient and widely used for structured clustering problems

- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
  - Groups points based on density
  - Detects arbitrary shaped clusters
  - Identifies noise/outliers in the dataset

These algorithms were applied to group similar songs together, enabling a **content-based music recommendation system**.

---

## 📈 Evaluation Metrics

- **Silhouette Score**
  - Evaluates cluster cohesion and separation
  - Used to determine the optimal number of clusters (`K`) for K-Means

- **Davies–Bouldin Index (DB Index)**
  - Measures cluster compactness and separation
  - Lower values indicate better clustering performance
  

---
## 📊 Visualizations

The system includes the following visualizations:

- **Cluster Scatter Plots** – Visual representation of song clusters based on feature similarity.
- **Feature Correlation Heatmaps** – Shows relationships between different Spotify audio features.
- **PCA Cluster Projections** – Dimensionality reduction used to visualize high-dimensional data in 2D space.
- **Audio Feature Distributions** – Distribution plots for attributes like energy, danceability, tempo, etc.

### Visualization Libraries Used

- **Matplotlib**
- **Seaborn**
- **Plotly**
- Audio-based clustering of songs.
- Song recommendation based on proximity within feature space.
- Comparison of different clustering methods using standard evaluation metrics.

---

## 🛠️ Technologies

- Python
- Scikit-learn
- Pandas / NumPy
- Plotly / Matplotlib for visualization
- Streamlit (optional, for web-based UI)

---
## 📦 Project Structure

- **SpotifyClusteringApp/**
  - **data/** – Raw and cleaned Spotify datasets
  - **models/** – Saved clustering models (K-Means, DBSCAN)
  - **notebooks/** – Jupyter notebooks for data exploration and experiments
  - **app/** – Streamlit application files for the interactive dashboard
  - **utils/** – Helper scripts and utility functions
  - **requirements.txt** – Project dependencies
  - **README.md** – Project documentation and overview


---
### 1. Clone the Repository

```bash
git clone https://github.com/rosh-nik15/SpotifyClusteringApp.git
cd SpotifyClusteringApp
```
###2. Create Virtual Environment
```bash
python -m venv venv
```
###4. Install Dependencies
```bash
pip install -r requirements.txt
```
###5. Run the Streamlit Application
```bash
streamlit run app.py
```
6. Open in Browser
http://localhost:8501
---

   
## 🚀 Future Improvements

Possible extensions for the project:

- **Spotify Web API Integration** – Fetch real-time song data and audio features directly from Spotify.
- **Deep Learning Audio Embeddings** – Use neural networks to learn richer song representations.
- **Hybrid Recommendation System** – Combine content-based and collaborative filtering techniques.
- **Automatic Playlist Generation** – Generate playlists based on cluster similarity and user preferences.
  .
  ---
## 🚀 Live Demo
   deployed on Streamlit Cloud:
   

