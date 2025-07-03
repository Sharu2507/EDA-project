# 📊 EDA Project Portfolio

Welcome to my exploratory data analysis (EDA) project repository! This repo contains two major projects:

- ✅ **Air Quality Data Analysis** (from UCI Machine Learning Repository)
- 🎧 **Spotify Track Audio Feature Analysis & Data Pipeline**

Each project is built using Python and showcases my skills in data wrangling, visualization, and API integration.

---

## 🌫️ Project 1: Air Quality Data Analysis

**Dataset Source:** [UCI Air Quality Dataset](https://archive.ics.uci.edu/dataset/360/air+quality)

### 🔍 Objective:
To perform exploratory data analysis on environmental air quality data collected in an Italian city, focusing on pollutant trends, missing data handling, and visual insights.

### 📌 Key Techniques Used:
- Data cleaning (handling missing values and inconsistent timestamps)
- Feature engineering for pollutant trends
- Time-series analysis and visualization
- Heatmaps and correlation plots using Seaborn and Matplotlib

### 🛠️ Tools & Libraries:
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `datetime`, `scikit-learn` (optional preprocessing)

---

## 🎧 Project 2: Spotify Track Audio Feature Analysis

**Dataset Source:** Spotify Web API

### 🔍 Objective:
To extract and analyze audio features (like danceability, energy, valence, etc.) of tracks using the Spotify Web API and explore their musical characteristics.

### 📌 What It Does:
- Connects to the Spotify API using `spotipy`
- Authenticates via OAuth
- Fetches track metadata and audio features
- Cleans and interprets song data (regex used for text cleanup)
- Lays the foundation for building music recommenders or mood classifiers

### 🛠️ Tools & Libraries:
- `spotipy`
- `requests`
- `pandas`
- `re` (for regex-based cleaning)

---

## 📂 Folder Structure

```bash
EDA-project/
├── airquality-analysis/
│   ├── air_quality_eda.ipynb
│   └── air_quality_dataset.csv
├── spotify-track-pipeline/
│   ├── spotify_data_pipeline.ipynb
│   └── requirements.txt
└── README.md

