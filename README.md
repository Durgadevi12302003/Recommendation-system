# Movie Recommendation System

## Overview
This project is a Movie Recommendation System designed to suggest movies based on user preferences and viewing history. Using cosine similarity on a dataset of Tamil movies, the system analyzes movie metadata to provide personalized recommendations. This project leverages machine learning techniques to enhance the user experience by delivering relevant and engaging content.

## Features
- **Content-Based Filtering**: Recommends movies based on metadata, such as genres, cast, and plot descriptions.
- **Cosine Similarity Algorithm**: Measures similarity between movies to find the best matches for a user's interests.
- **Tamil Movie Dataset**: Specifically curated to recommend Tamil movies, enhancing relevance for users interested in this genre.
- **User-Friendly Interface**: Provides easy navigation for users to explore recommended titles.

## Project Structure
- **data/**: Contains the Tamil movie dataset.
- **src/**: Core code for the recommendation engine, including preprocessing, similarity calculations, and model functions.
- **app.py**: Main application file to run the recommendation system.
- **README.md**: Documentation and instructions for using the project.
- **requirements.txt**: List of dependencies required for the project.

## How It Works
1. **Data Preprocessing**: The dataset is cleaned and prepared, with movie features such as genre, actors, and plot keywords extracted.
2. **Cosine Similarity Calculation**: A similarity score is calculated between movies based on their feature vectors.
3. **Recommendation Generation**: Given a selected movie, the system identifies the top movies with the highest cosine similarity scores and presents them as recommendations.

## Installation
To set up and run the Movie Recommendation System locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
2. **Navigate to the Project Directory**
     ```bash
     cd movie-recommendation-system

