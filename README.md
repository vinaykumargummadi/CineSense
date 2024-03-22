# CineSense: Movie Recommendation System

## Overview

CineSense is a movie recommendation system developed using natural language processing (NLP) techniques. The system predicts movie titles based on user descriptions or explanations. It utilizes a dataset containing movie-related information from sources like IMDb or Rotten Tomatoes, including movie titles, descriptions, reviews, ratings, and metadata.

## Data Sources

The dataset used in this project contains movie-related information sourced from IMDb and Rotten Tomatoes. It includes movie titles, descriptions, reviews, ratings, and metadata. The dataset consists of (17712, 22) rows and columns.

## Implementation Plan

### 1. Data Preprocessing

- Address missing values
- Perform text processing
- Extract relevant features from the dataset

### 2. Model Training



### 3. Google Colab Setup

- Utilize Google Colab for development
- Leverage its free GPU/TPU resources and integrated notebook environment

### 4. Project Structure

- Organize the project directory with separate folders:
  - Data
  - Notebooks
  - Models
  - Utilities
- Structure the Streamlit app code in a modular manner for clarity and organization

### 5. Streamlit UI

- Build a user interface using Streamlit for model inference and result display
- Deploy the app to a hosting platform like Streamlit Sharing or Heroku

### 6. Next Steps

- Refine model performance
- Enhance UI functionality
- Deploy the app for public access

## Additional Steps Discussed

- Utilizing Named Entity Recognition (NER) to extract entities such as cast names, production companies, release years, and budget information from user prompts
- Implementing K-Nearest Neighbors (KNN) with cosine similarity to find movies with descriptions closely resembling the user's prompt
- Considering excluding the movie title from the user's input for NER-based filtering, as it's likely already provided
- Assigning working titles for the approaches: "EntityFilter" for NER-based filtering and "SimilarityMatcher" for KNN with cosine similarity
- Planning to focus on implementing and fine-tuning each approach individually before considering integration

## Usage

1. Clone the repository:  
`git clone https://github.com/vinaykumargummadi/CineSense`

## Contributions
Vinay Kumar Gummadi (https://github.com/vinaykumargummadi)

