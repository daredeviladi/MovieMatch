# MovieMatch - Movie Recommendation System

MovieMatch is a movie recommendation system built using machine learning concepts and deployed with the Streamlit library on Heroku. This project aims to provide personalized movie recommendations based on user preferences, leveraging both collaborative filtering and content-based filtering techniques.

## Problem Statement
The goal of MovieMatch is to recommend movies to users based on their input movie choice. By analyzing movie data from The Movie Database (TMDB), including genres, keywords, cast, and crew, the system aims to enhance the viewing experience for users by suggesting relevant and personalized content.


## Data Overview
Dataset-> [Link to Download dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- **Source:** TMDB
- **Data:** Consists of information for 5000 movies, including title, genres, keywords, overview, cast, crew, and more.
- **Data Cleaning and Preparation:** The data is cleaned, null values are handled, and relevant columns are selected for analysis. Textual data is processed using natural language processing techniques.

## Implementation
1. **Data Preparation:** Exploration of columns, handling null values, and merging datasets.
2. **Data Cleaning:** Text data is processed, including extracting genres, keywords, cast, and crew information.
3. **Feature Extraction:** Relevant features are extracted for analysis, and a combined dataset is created.
4. **Vectorization:** CountVectorizer is used to convert textual data into numeric data for further processing.
5. **Similarity Calculation:** Cosine similarity is employed to measure the similarity between movies based on their textual descriptions.
6. **Model Deployment:** The recommendation system is deployed on Heroku using Streamlit, providing users with a user-friendly interface to discover movie recommendations.

## Key Features
- Collaborative filtering and content-based filtering techniques
- User-friendly interface for inputting movie preferences
- Top 10 movie recommendations based on input movie choice
- Integration with TMDB to fetch additional movie information, including posters


## Contributing
Contributions to MovieMatch are welcome! Whether it's bug fixes, feature enhancements, or documentation improvements, feel free to open an issue or submit a pull request.




