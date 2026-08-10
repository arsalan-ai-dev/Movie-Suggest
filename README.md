# 🍿 Movie Suggest — AI Movie Recommendation System

A content-based movie recommendation system that recommends similar movies based on their plot descriptions.

The system uses **TF-IDF vectorization** and **Cosine Similarity** to identify movies with similar content and integrates the **TMDB API** to display live movie posters and ratings.

---

## 🚀 Live Demo

🎬 **Live Application:**  
https://movie-suggest-production-bdc5.up.railway.app

> Deployed on Railway with an interactive Streamlit interface.

---

## ✨ Features

- 🎬 **Movie Recommendations** — Get 10 similar movies for a selected movie.
- 🧠 **TF-IDF Vectorization** — Converts movie descriptions into numerical feature vectors.
- 📐 **Cosine Similarity** — Measures similarity between movies.
- 📅 **Year Filter** — Filter recommendations by release year.
- ⭐ **Live Ratings** — Retrieves current movie ratings from TMDB.
- 🖼️ **Movie Posters** — Displays movie posters using the TMDB API.
- 🖥️ **Interactive UI** — Built with Streamlit.
- ☁️ **Cloud Deployment** — Deployed on Railway.

---

## 🏗️ System Architecture

```text
                    +----------------------+
                    |        User          |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Streamlit Interface  |
                    |   Select a Movie      |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    |   Movie Dataset      |
                    |  Movie Plot/Summary  |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    |  TF-IDF Vectorizer   |
                    | Text → Feature       |
                    |       Vectors        |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Cosine Similarity    |
                    | Compare Movie        |
                    | Feature Vectors      |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Top 10 Similar Movies |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    |      TMDB API        |
                    | Posters + Ratings    |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Recommended Movies   |
                    | Posters + Ratings    |
                    +----------------------+


