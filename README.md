# Spotify Tracks Dataset :musical_note:


This repository contains all the project files for the final group hackathon in Code Institute's, Data Analytics with AI bootcamp.

## **1\. Project Overview & Goal**

### **Dataset & Source**

This project utilises the [Spotify Tracks dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) sourced from Kaggle, contains 114,001 individual tracks and 20 attributes.

The dataset contains Spotify tracks over a range of 125 genres. Some tracks contain some audio features associated with it. The attributes contain specific characteristics about the song. (Track ID, the artist, the album, track name and track genre) As well as measurable track data. (popularity, duration minutes, danceability, energy, key, loudness, mode, speechiness, acousticness, intstrumentalness, liveness, valence, tempo and time signature)

### **Project Overview**

Our project focuses on analysing Spotify data trends of music listeners. As it is the world's most popular audio streaming platform, with over 100 million hours of audio listened to per day, analysing its data is essential to understand industry insights. We aim to explore current listening trends, understand what music drives most popularity, analyse audio feature distributions.

### **Key questions and Hypothesis to be explored:**

**1)** What drives popularity in the music industry?

- H1: More energetic tracks are more popular

- H2: Louder tracks higher popularity

- H3: Instrumental tracks are less popular

**2)** Which music structure is favored amongst listeners?

- H4: Major- key songs are more popular than minor-key songs

- H5: Extremely fast or slow tempos reduce popularity

- H6: High-valence (happier) tracks are more popular

**3)** How does genre play into the popularity of a song?

- H7: Popularity drivers differ by genre category

**4)** How do Acoustic tracks play into the popularity of a song?

- H8: Acoustic tracks are less popular on average than non-acoustic tracks

**5)** Do artists who own more tracks increase their chance of popularity

- H9: Artists with more tracks have higher average popularity

### **Machine Learning**

Create a Machine learning model to predict the popularity of a song using ML and segment song types into clusters that can generate insight and drive strategy for user recommendations. Additionally, build a Spotify content based recommendation system to improve user experience.

### **Dasboard and Project board**

Link to project dashboard: 

Link to project board: https://trello.com/b/OLkLmkge/team-2-spotify-tracks-dataset-final-hackathon 

## **2\. Repository Structure**

## **3\. Tools & Technologies**

- **Trello**
- **Python (python version 3.13) , Pandas, NumPy, Matplotlib, Seaborn, an eda module was also developed**
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
- Tableau dashboard with interactive visuals
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

## **8\. Key insights** 
- The largest number of tracks belong to rock, pop, metal and Brazilian.
- The majority of tracks have a high trend towards high energy (dancebility) and exhibit high loudness.
- The majority of tracks contain vocal rather than instrumental
- The majority of tracks are studio based and not live recordings.
- Most popular genres include hip-hop, chill and sad
- Genres with the highest hit rate include indie, reggae and hip -hop (more than 10% of tracks reaching >70)
- The most popular songs however are likely to be live recordings.
- According to the regression model, audio features explain 54% of popularity variation, wwhich is expected as popularity depends on external factors. A mixture of sound texture, rhyth, emotion and vocal presence drives popularity.
- Song cluster profiles include 0- Instrumental, 1- Light dance songs, 2- Disco/pop ans 3- Fast & Intense

## **7\. How to Run the Project Locally**

**Clone the Repository**

git clone \[<https://github.com/48at9vev-code/Spotify-Tracks-Dataset-CI_Team-2\>]

**Run the Notebook**

Open 01-03_elt_eda_data_cleaning.ipynb and 04_ml-analysis.ipynb and run all cells sequentially. The notebook will automatically download the data, run the ETL pipeline, and generate all seaborn/matplotlib visualizations.

## **8\. Ethical considerations concerning privacy**

Spotify is obligated to communicate with users exactly what data is collected and why, particularly concerning device sensor data, microphone usage and browsing history. It is expected to comply with GDPR.

Ethical usage requires avoiding excessive tracking, .i.e. analysing how users make specific volume adjustments and should adhere to the principle of collecting only minimum amount of data.

As AI becomes more integral, it must ensure the algorithim does not perpetuate biases and users are aware of how the models use data. 

## **9\. Social and legal Implications of the data handling and findings**

Spotify's data handling raises significant social concerns around privacy, cultural influence, algorithmic bias and artost fairness, wwhile legally complying with GDPR, data security, profiling transparency and cross-border data regulations that have severe penalties for misuse or non-compliance.

## **10\. User stories**

As a team studying data analysis, we wanted to analyse current trends on spotify's data base that could provide us with more insight on what is the most popular form of music, what structure of music is the most popular and  which artists puts out the most music and if it influences popularity. We also wanted to create a Machine learning model to predict the popularity of a song using ML and segment song types into clusters that can generate insight and drive strategy for user recommendations. Additionally, build a Spotify content based recommendation system to improve user experience.


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
