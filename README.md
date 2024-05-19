<a name="top"></a>
# Movie Recommendation Model and Feature Analysis of Streaming Services

> ## Table of Contents
> - [Introduction](#introduction)
> - [Data](#data)
>   - [Raw Data Sources](#raw-data-sources)
>   - [Content](#content)
>  - [Installation](#installation)
> - [Credits](#credits)

## Introduction
In an era of abundant content, users often face difficulty in choosing what to watch. Our goal is to develop a robust recommendation model that simplifies this process, improving user satisfaction and engagement with streaming platforms.


This project aims to build a movie/show recommendation system that only considers movies found on subscribed streaming services. By analyzing features from streaming services, we aim to enhance user experience through personalized movie suggestions.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Data

### Raw Data Sources
I primarily used [Kaggle](https://www.kaggle.com/) to find my streaming datasets. I will hyperlink each dataset for documentation purposes and in the case anyone is interested in delving further into the project:
- [Amazon Prime Video](https://www.kaggle.com/datasets/victorsoeiro/amazon-prime-tv-shows-and-movies?select=titles.csv)
- [AppleTV+](https://www.kaggle.com/datasets/dgoenrique/apple-tv-movies-and-tv-shows?select=titles.csv)
- [Disney+](https://www.kaggle.com/datasets/victorsoeiro/disney-tv-shows-and-movies?select=titles.csv)
- [HBO Max](https://www.kaggle.com/datasets/dgoenrique/hbo-max-movies-and-tv-shows?select=titles.csv)
- [Netflix](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies?select=titles.csv)
- [Paramount+](https://www.kaggle.com/datasets/victorsoeiro/paramount-tv-shows-and-movies?select=titles.csv)

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

### Content
In each dataset, there are 15 features:

- `id`: The title ID on JustWatch.
- `title`: The name of the title.
- `type`: TV show or movie.
- `description`: A brief description.
- `release_year`: The release year.
- `age_certification`: The age certification.
- `runtime`: The length of the episode (SHOW) or movie.
- `genres`: A list of genres.
- `production_countries`: A list of countries that - produced the title.
- `seasons`: Number of seasons if it's a SHOW.
- `imdb_id`: The title ID on IMDB.
- `imdb_score`: Score on IMDB.
- `imdb_votes`: Votes on IMDB.
- `tmdb_popularity`: Popularity on TMDB.
- `tmdb_score`: Score on TMDB.


## Installation
To set up this project locally, follow these steps:
- Clone the repository:
``` console
git clone https://github.com/RyHops/MovieRec_FeatureAnalysis.git
```
- I wrote this using a local path for the datafiles. In order to run tyhe script, download `Data\Raw` and replace each respective path.
- Read and run each cell chronologically.

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>

## Credits
+ *Ryan Hopkins*

<div align="right" style="text-align: right;"><a href="#top">Back to Top</a></div>
