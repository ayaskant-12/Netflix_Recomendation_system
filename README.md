# Netflix Recomendation System

## Data Loading and Exploration

The code starts by loading the Netflix dataset from a CSV file and performs basic exploratory data analysis (EDA).
This includes checking for missing values and displaying the structure of the dataset using the head() function.

## Text Preprocessing

The "Title" column is preprocessed using various text preprocessing techniques such as lowercasing, removal of URLs, punctuation, numbers, and stopwords. 
Additionally, stemming is applied to reduce words to their root form.

## Text Feature Extraction

TF-IDF vectorization is used to convert the textual data in the "Genres" column into numerical vectors. 
This process transforms the text data into a format suitable for computing similarity between different titles.

## Recommendation Function

A function called netflix_recommendation is defined to recommend similar titles based on cosine similarity computed using TF-IDF vectors. 
Given a title as input, the function returns a list of similar titles.

## Clustering

K-means clustering is performed on the dataset after one-hot encoding categorical features (in this case, "Genres"). 
The optimal number of clusters is determined using the silhouette score and the elbow method.

## Visualization

The elbow method is visualized to find the optimal number of clusters. Additionally, a scatter plot of "Rating" vs. 
"IMDb Score" is created, with points colored by cluster membership, to observe any patterns or groupings within the data.

## Follow

follow me on [github](https://github.com/ayaskant-12)

follow me on [instagram](https://www.instagram.com/ayaskant_dash_03/)
