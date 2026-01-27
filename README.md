# Spotify Tracks Dataset

Spotify Tracks Dataset - Project Hackathon of Team 2. Code Institute.

python version 3.13

This repository contains all the project files for the final group hackathon in Code Institute's, Data Analytics with AI bootcamp.

**1\. Project Overview & Goal**

**Dataset & Source**

This project utilises the [Spotify Tracks dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) sourced from Kaggle, contains 114,001 individual tracks and 20 attributes.

The dataset contains Spotify tracks over a range of 125 genres. Some tracks contain some audio features associated with it. The attributes contain specific characteristics about the song. (Track ID, the artist, the album, track name and track genre) As well as measurable track data. (popularity, duration minutes, danceability, energy, key, loudness, mode, speechiness, acousticness, intstrumentalness, liveness, valence, tempo and time signature)

**Project Overview**

Our project focuses on analysing Spotify data trends of music listeners. As it is the world's most popular audio streaming platform, with over 100 million hours of audio listened to per day, analysing its data is essential to understand industry insights. We aim to explore current listening trends, understand what music drives most popularity, analyse audio feature distributions.

**Key question and Hypothesis to be explored:**

- How does the mood of a song drive popularity?

H1: High energy songs have higher popularity

This project will also build a Machine learning model that recommends a song type based on the users whom have similar listening preferences.

**2\. Repository Structure**

**3\. Tools & Technologies**

- **Trello**
- **Python, Pandas, NumPy, Matplotlib, Seaborn**
- **Jupyter Notebook**
- **GitHub (Version Control)**
- **Tableau or Power Bi?**

**4\. Target Audience**

The dashboard and interactive tool are intended for:

- **Music Listeners-** Those who are looking to understand global music trends and those who are looking to receive music recommendations based on specific characteristics of a song like genre or danceability.
- **Spotify business executives and music producers -** For artists, record labels and Spotify executives to understand the market, improve playlist engagement and identify high-potential tracks with a specific audience.

**5\. Expected Deliverables**

Our final outputs for the hackathon will be:

- Clean, structured dataset ready for analysis
- EDA- Identify key correlations between attributes and answer hypothesis
- Machine learning model for song recommendations
- Power BI/Tableau dashboard with interactive visuals
- Project documentation (e.g. README, Project Proposal etc)
- Final presentation summarising findings, insights, and recommendations

**6\. Data Transformation Summary**

Need to write this up!!!

**7\. How to Run the Project Locally**

**Clone the Repository**

git clone \[<https://github.com/48at9vev-code/Spotify-Tracks-Dataset-CI_Team-2\>]

**Run the Notebook**

Open spotify-tracks-etl.ipynb and 01_etl.ipynb run all cells sequentially. The notebook will automatically download the data, run the ETL pipeline, and generate all seaborn/matplotlib visualizations.

**8\. Ethical considerations concerning privacy**

**9\. Social and legal Implications of the data handling and findings**

**10\. User stories**

**11\. Team Members & Roles (Team 2)**

These were the team members involved in this project and their main roles:

**Project Manager**

- Define the scope of the project
- Decide target user and target variable
- Set up GitHub repo and Trello Timeline

**Data Architect- ETL**

- Load Kaggle dataset
- Handle missing values and duplicates. Standardise genres, feature formatting
- Produce a clean table for Machine learning and further EDA analysis

**Data Analyst-EDA and ML**

- Explore key trends and identify strong correlation, making Genre-wise and mood-based comparisons
- Build a simple and explainable predictive model that recommends songs to the user. (KMeans/ Regression)
- Interpret cluster in business terms

**Data visualisation & story telling**

- Built the interactive dashboard and visualisations (Tableau).
- Designed user-friendly layouts and filter systems for exploring the data.
- Integrated insights into visual storytelling for the final project deliverables.

**Credits**
