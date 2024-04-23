# Spotify-Tracks-Analytics-and-Prediction






Kaggle Notebook: https://www.kaggle.com/code/saharhamdi/spotify-analysis-and-prediction



In this project, we aim to perform exploratory data analysis (EDA) on the Spotify dataset to gain insights into various aspects of the tracks. We will visualize distributions, explore relationships between features, investigate correlations between numerical variables, and Build a Prediction Models.



## **Dependencies**

The code in this project requires the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn



## **Dataset**

- The dataset used in this analysis is the Ultimate Spotify Tracks Database, which can be found [here](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db). It contains information about over 160,000 tracks from Spotify, including various musical features and popularity ratings.



## **Data Exploration**

We perform the following steps in our data exploration:

* Loading the Spotify dataset
* Checking for null values and handling missing values
* Exploring descriptive statistics for numerical variables
* Visualizing distributions and relationships between variables
* Analyzing the distribution of genres, artists, and tracks
* Investigating the count of keys, modes, and time signatures


## **Correlation Matrix**

- We construct a correlation matrix to identify relationships between numerical features in the Spotify dataset. This helps us understand which variables are correlated and how strongly they are related.



## **Relationships Between Features and Popularity**

- we explore the relationships between data features and popularity ratings. We analyze how various musical characteristics impact the popularity of tracks.


## **Feature Engineering**

- we added new columns for dataset, renamed sum Columns, Found relationships between coulmns, and then dropped the unnecessary columns.



## **Data Scaling**

- I used MinMax Scaler.



## **Mosdel Evaluation**

- I used three Models:
   1. Linear Regression --> accuracy = 90.21%.
   2. Random Forest --> accuracy = 92.77%.
   3. Dicession Tree --> accuracy = 13%.
 
  Then I visualized The accuracy of Three Models.
