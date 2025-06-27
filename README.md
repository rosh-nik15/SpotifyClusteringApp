# 🎧 Spotify Music Recommendation System

## 🚀 Project Overview

The **Spotify Music Recommendation System** clusters songs based on their audio features to recommend similar tracks to users. This unsupervised learning approach allows music discovery by analyzing song attributes and grouping them into meaningful clusters.

---

## 🎯 Goal

- To build a system that recommends songs by clustering them based on their audio features using machine learning algorithms.

---

## 📊 Dataset

- **Name:** Spotify Songs Dataset  
- **Source:** Contains audio features such as danceability, energy, tempo, acousticness, valence, etc., for a large number of songs.

---

## 🧠 Algorithms Used

- **K-Means Clustering**
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**

These algorithms were applied to group similar songs together, enabling content-based music recommendation.

---

## 📈 Evaluation Metrics

- **Silhouette Score:**  
  Used to evaluate and tune the number of clusters (`K`) in K-Means for optimal grouping.

- **Davies-Bouldin Index (DB Index):**  
  Measures the compactness and separation of clusters to compare the effectiveness of different clustering algorithms.

---

## 💡 Features

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

spotify-recommender/
│
├── data/ # Raw and cleaned datasets
├── models/ # Saved clustering models
├── notebooks/ # Jupyter notebooks for exploration
├── app/ # Streamlit app files (optional)
├── utils/ # Helper scripts and functions
├── README.md # Project overview and documentation

---


---

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spotify-recommender.git
   cd spotify-recommender
2. Install dependencies:
    ```bash
   pip install -r requirements.txt

4. Run the notebook or Streamlit app:
    ```bash
    streamlit run app

