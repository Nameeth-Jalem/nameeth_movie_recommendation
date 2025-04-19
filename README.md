# nameeth_movie_recommendation
![image alt](https://github.com/Nameeth-Jalem/nameeth_movie_recommendation/blob/main/Process-flow.png?raw=true)
<div align="center">
  <h1>🎬 Movie Recommendation System</h1>
  <p><strong>A content-based movie recommendation engine using Cosine Similarity.</strong></p>

  <p>
    <a href="https://github.com/Nameeth-Jalem/Movie-Recommendation/stargazers"><img src="https://img.shields.io/github/stars/Nameeth-Jalem/Movie-Recommendation?style=social" /></a>
    <a href="https://github.com/Nameeth-Jalem/Movie-Recommendation/network/members"><img src="https://img.shields.io/github/forks/Nameeth-Jalem/Movie-Recommendation?style=social" /></a>
    <a href="https://github.com/Nameeth-Jalem/Movie-Recommendation/issues"><img src="https://img.shields.io/github/issues/Nameeth-Jalem/Movie-Recommendation" /></a>
  </p>
</div>

---

## 🧠 Project Overview

This project implements a **content-based movie recommendation system** using **Cosine Similarity** to recommend movies based on their similarity in terms of features (such as genre, director, and keywords).

### **Cosine Similarity**:
The system computes the cosine similarity between movies based on their attributes (like genres, keywords, and descriptions) and suggests the most similar movies to the user’s input movie.

---

## 📁 Project Structure

Movie-Recommendation/ ├── Process-flow.png # Visual representation of the recommendation process ├── Movie_recommendation.ipynb # Jupyter notebook for building and testing the recommendation engine ├── app.py # Main application file for the movie recommendation web app ├── requirements.txt # Python dependencies for the project ├── gitignore # Files to exclude from version control ├── movie_dict.pkl # Pickled movie dataset dictionary for easy access ├── procfile # File used for deployment (e.g., on Heroku) └── setup.ssh # SSH setup configuration for app deployment
