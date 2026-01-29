# Spotify Tracks Dataset :musical_note:

python version 3.13

This repository contains all the project files for the final group hackathon in Code Institute's, Data Analytics with AI bootcamp.

**1\. Project Overview & Goal**

## **Dataset & Source**

This project utilises the [Spotify Tracks dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) sourced from Kaggle, contains 114,001 individual tracks and 20 attributes.

The dataset contains Spotify tracks over a range of 125 genres. Some tracks contain some audio features associated with it. The attributes contain specific characteristics about the song. (Track ID, the artist, the album, track name and track genre) As well as measurable track data. (popularity, duration minutes, danceability, energy, key, loudness, mode, speechiness, acousticness, intstrumentalness, liveness, valence, tempo and time signature)

## **Project Overview**

Our project focuses on analysing Spotify data trends of music listeners. As it is the world's most popular audio streaming platform, with over 100 million hours of audio listened to per day, analysing its data is essential to understand industry insights. We aim to explore current listening trends, understand what music drives most popularity, analyse audio feature distributions.

### **Key questions and Hypothesis to be explored:**

1) What drives popularity in the music industry?

- H1: More energetic tracks are more popular

- H2: Louder tracks higher popularity

- H3: Instrumental tracks are less popular

2) Which music structure is favored amongst listeners?

- H4: Major- key songs are more popular than minor-key songs

- H5: Extremely fast or slow tempos reduce popularity

- H6: High-valence (happier) tracks are more popular

3) How does genre play into the popularity of a song?

- H7: Popularity drivers differ by genre category

4) How do Acoustic tracks play into the popularity of a song?

- H8: Acoustic tracks are less popular on average than non-acoustic tracks

5) Do artists who own more tracks increase their chance of popularity

-H9: Artists with more tracks have higher average popularity 

Link to project dashboard: 

Link to project board: https://trello.com/b/OLkLmkge/team-2-spotify-tracks-dataset-final-hackathon 

## **2\. Repository Structure**

## **3\. Tools & Technologies**

- **Trello**
- **Python, Pandas, NumPy, Matplotlib, Seaborn, an eda module was also developed**
- **Jupyter Notebook**
- **GitHub (Version Control)**
- **Tableau**

## **4\. Target Audience**

The dashboard and interactive tool are intended for:

- **Music Listeners-** Those who are looking to understand global music trends and those who are looking to receive music recommendations based on specific characteristics of a song like genre or danceability.
- **Spotify business executives and music producers -** For artists, record labels and Spotify executives to understand the market, improve playlist engagement and identify high-potential tracks with a specific audience.

## **5\. Expected Deliverables**

Our final outputs for the hackathon will be:

- Clean, structured dataset ready for analysis
- EDA- Identify key correlations between attributes and answer hypothesis
- Machine learning model for song recommendations and cluster anlysis of the most popular genre
- Power BI/Tableau dashboard with interactive visuals
- Project documentation (e.g. README, Project Proposal etc)
- Final presentation summarising findings, insights, and recommendations

## **6\. Data Transformation Summary**

| **Original column** | **Transform applied** | **Purpose/ additional notes** |
| --- | --- | --- |
| **'Unamed:0 column'** | **Column was dropped** | **Ambiguity not useful for analysis** |
| **Row with missing data** | **Row was dropped** | **Not useful for analysis** |
| **'artists'** | **Formatting- remove spaced before and after column values** | **Values can be better compared and identified** |
| **'track_id'** | **Formatting- remove spaced before and after column values** | **Values can be better compared and identified** |
| **'track_name'** | **Formatting- remove spaced before and after column values** | **Values can be better compared and identified** |
| **'album_name'** | **Formatting- remove spaced before and after column values** | **Values can be better compared and identified** |
| **'track_genre'** | **Formatting- remove spaced before and after column values** | **Values can be better compared and identified** |
| **'track_name' and 'track_genre'** | **Duplicated values in both for both columns dropped** | **While result makes sense. (It could be the same song in a different language) knowing that difference is not useful for analysis** |
| **'track_genre'** | **Saved in a different file for analysis** | **Aid Dashboard** |

## **7\. How to Run the Project Locally**

**Clone the Repository**

git clone \[<https://github.com/48at9vev-code/Spotify-Tracks-Dataset-CI_Team-2\>]

**Run the Notebook**

Open XXXX run all cells sequentially. The notebook will automatically download the data, run the ETL pipeline, and generate all seaborn/matplotlib visualizations.

## **8\. Ethical considerations concerning privacy**

## **9\. Social and legal Implications of the data handling and findings**

## **10\. User stories**

## **11\. Team Members & Roles (Team 2)**

These were the team members involved in this project and their main roles:

### **Project Manager**

- Define the scope of the project
- Decide target user and target variable
- Set up GitHub repo and Trello Timeline

### **Data Architect- ETL**

- Load Kaggle dataset
- Handle missing values and duplicates. Standardise genres, feature formatting
- Produce a clean table for Machine learning and further EDA analysis

### **Data Analyst-EDA and ML**

- Explore key trends and identify strong correlation, making Genre-wise and mood-based comparisons
- Build a simple and explainable predictive model that recommends songs to the user. (KMeans/ Regression)
- Interpret cluster in business terms

### **Data visualisation & story telling**

- Built the interactive dashboard and visualisations (Tableau).
- Designed user-friendly layouts and filter systems for exploring the data.
- Integrated insights into visual storytelling for the final project deliverables.

### **Credits**

\- Spotify Tracks Dataset (Kaggle)
<https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset>

\- Spotify Web API - Audio Features
<https://developer.spotify.com/documentation/web-api/reference/get-audio-features>

\- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
<https://pandas.pydata.org/> | <https://numpy.org/> | <https://scikit-learn.org/> | <https://matplotlib.org/> | <https://seaborn.pydata.org/>
\- K-Means Clustering - Lloyd (1982)

\- Silhouette Score - Rousseeuw (1987)

\- Random Forests - Breiman (2001)

\- An Introduction to Statistical Learning - James et al. (2013)

\- Kaggle Learn - <https://www.kaggle.com/learn>

\- AI Assistance: ChatGPT / GitHub Copilot / Claude AI (used for support; outputs reviewed and adapted)
