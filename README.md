<a name="top"></a>
# Movie Recommendation Model and Feature Analysis of Streaming Services

> ## Table of Contents
> - [Introduction](#introduction)
> - [Motivation](#motivation)
> - [Data](#data)
>   - [Raw Data Sources](#raw-data-sources)
>   - [Data Preparation and Preprocessing](#data-preparation-and-preprocessing)
>  - [Installation](#installation)
>  - [Analysis / Model Building](#analysis-\-model-building)
>      - [Exploratory Data Analysis](#exploratory-data-analysis)
>      - [Recommendation Model](#recommendation-model)
>           - [Collaborative Filtering](#collaborative-filtering)
>           - [Content-Based Filtering](#content-based-filtering)
> - [Results and Discussion](#results-and-discussion)
> - [Credits](#credits)

## Introduction
This project aims to build a movie recommendation system using collaborative and content-based filtering techniques. By analyzing features from streaming services, we aim to enhance user experience through personalized movie suggestions.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Motivation
In an era of abundant content, users often face difficulty in choosing what to watch. Our goal is to develop a robust recommendation model that simplifies this process, improving user satisfaction and engagement with streaming platforms.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Data

### Raw Data Sources
We utilize several datasets consisting of movie ratings, user interactions, and movie metadata, primarily sourced from:
- *[MovieLens](https://grouplens.org/datasets/movielens/)*: A large dataset of movie ratings by users.
- *[IMDb](https://www.imdb.com/interfaces/)*: Metadata for movies, including genres, actors, and directors.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Data Preparation and Preprocessing

***(Users do not need to run these scripts, as the cleaned and preprocessed datasets are already available in the repository.)***

The `Code/Prep` directory contains scripts used for data cleaning and preprocessing, crucial for preparing the datasets used in our analyses. These scripts are included for transparency and for those interested in understanding or replicating our preprocessing steps.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

### Available Data

The preprocessed datasets used for analysis are available in the `Data/` directory. These datasets have been cleaned, merged, and formatted for direct use in the analysis scripts provided in the `Code/Analysis` directory.

> Links to the raw datasets used for data preparation and preprocessing can be found in the `ExternalData.txt` file.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Installation
To set up this project locally, follow these steps:
1. Clone the repository:
``` console
git clone https://github.com/RyHops/MovieRec_FeatureAnalysis.git
```
2. Install required libraries:
``` console
pip install -r requirements.txt
```

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Analysis / Model Building
Run the following scripts, found in the `Code/Analysis` directory, to analyze the preprocessed datasets found in the `Data/` directory:

### Exploratory Data Analysis

- `EDA_Movies.ipynb`
  - **Description**: This notebook performs exploratory data analysis on the movie dataset. It processes data from CSV files, visualizes user ratings distribution, and explores the correlation between different movie features.
    - **Input**: `Data/movies.csv`, `Data/ratings.csv`
    - **Output**: The notebook generates a series of plots visualizing ratings distribution, genre popularity, and the correlation between movie features.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

### Recommendation Model

#### Collaborative Filtering

- `Collaborative_Filtering.ipynb`
  - **Description**: This notebook implements collaborative filtering using matrix factorization techniques to predict user ratings for movies.
    - **Input**: `Data/ratings.csv`
    - **Output**: Predicted ratings for each user-movie pair, and evaluation metrics such as RMSE and MAE.

#### Content-Based Filtering

- `Content_Based_Filtering.ipynb`
  - **Description**: This notebook implements content-based filtering using movie metadata to recommend movies based on their features.
    - **Input**: `Data/movies.csv`
    - **Output**: Movie recommendations for each user based on their preferences and movie features.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Results and Discussion
The results section provides a comprehensive analysis of the model performance, including evaluation metrics and visualizations of the recommendation effectiveness. We discuss the strengths and limitations of each approach and suggest potential improvements.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Credits
+ *Ryan Hopkins*
+ *Collaborators if any*

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

---

Feel free to adjust any details or add additional information as needed.
