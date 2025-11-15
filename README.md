# Movie-Recommendation-System
A simple and interactive Movie Recommendation system built using Python, Machine Learning and Streamlit. This project recommends movies similar to one selected by the user using content-based filtering. 

# How the Recommendation System works
The system analysis multiple attributes of the dataset like Overview, Genre, Keywords, Cast and Crew. These attributes are combined and converted into vectors using TF-IDF Vectoriation. The cosine similarity is used to find the movies closest to one selected by the user.

# Dataset Used
The dataset used for this project is TMDB 5000 Movie Dataset, which was sourced from Kaggle.
link: [Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
  

# Technology Used
- Python
- Streamlit
- Scikit-learn
- pickle
- nltk
- Requests (TMBD API)

# TMBD API usage
The movie poster for each of the movies in this project was fetched using TMBD API:
https://api.themoviedb.org/3/movie/{movie_id}?api_key=YOUR_API_KEY (replace the 'API_KEY' with your own API key)

# Run the project
python -m streamlit run app.py


