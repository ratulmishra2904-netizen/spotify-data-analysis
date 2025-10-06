**Spotify Track Data Analysis**
This repository contains an exploratory data analysis (EDA) of a dataset of Spotify tracks. The primary goal of this project is to uncover interesting relationships, trends, and patterns within the audio features (like danceability, energy, loudness, and tempo) and their correlation with track popularity.

The analysis is performed within a Jupyter Notebook, providing a step-by-step walkthrough of the data cleaning, visualization, and interpretation process.

**Project Files**
**spotifyDataSet.ipynb:** The main Jupyter Notebook containing all the Python code for data loading, cleaning, exploratory analysis, and visualization.

**spotify_tracks.csv:** The primary dataset containing track information, including audio features and popularity metrics.



**Key Analysis Sections**
The spotifyDataSet.ipynb notebook covers the following areas:

* Data Loading and Initial Inspection: Checking data types, identifying missing values, and viewing the first few rows.

* Data Cleaning: Handling duplicates and potential outliers.

* Exploratory Data Analysis (EDA): Calculating descriptive statistics for key numerical features.

* Feature Distribution Visualization: Using histograms and box plots to understand the distribution of audio features (e.g., loudness, tempo, valence).

* Correlation Analysis: Investigating the relationships between audio features and the target variable, popularity, using correlation matrices and scatter plots.

**Findings (Example)**
* Initial visualizations suggest a moderate positive correlation between high energy and danceability scores.

* The popularity of a track does not seem to correlate strongly with a single feature, but rather a combination of characteristics. 

* Duration of songs are declining year by year

* English is the language of most of the songs followed by Tamil

* More songs are being created now with low valence music.

* Top artists of every decade in top 3 popular language  (English , Korean , Hindi) 

Songs with low acoustics , high to moderate danceability and highly energetic are getting more popularity in 2020’s decade



Contributing
Feel free to open issues or submit pull requests if you have suggestions for further analysis or improvements to the data visualization.
