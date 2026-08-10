# 🍿 Movie Suggest

A content-based movie recommendation system. Pick a movie and get 10 similar recommendations with posters and ratings.

🔗 **Live Demo**: [Movie Suggest Live](https://movie-suggest-production-bdc5.up.railway.app)

---

## ✨ Features

- **10 Similar Movie Recommendations**: Uses TF-IDF vectorization and Cosine Similarity on 5,000+ movie plot summaries.
- **Year Filter**: Filter recommendations by release year range (1960–2026).
- **Live Movie Data**: Fetches real-time movie posters and ratings via the TMDB API.
- **Interactive UI**: Built with Streamlit for a seamless, responsive user experience.
- **24/7 Cloud Deployment**: Hosted on Railway with instant inference response times.

---

## 📂 Project Structure

```text
movie-recommender/
├── app.py                  # Main Streamlit application
├── movies_metadata.csv     # Dataset (5,000+ movies)
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── screenshots/            # Application screenshots
    ├── homepage.png        # Main dashboard
    └── response.png        # Recommendations view
---

## 🚀 How to Run Locally

### Prerequisites
- Python 3.10 or higher
- TMDB API key (free)

### Installation

1. **Clone the repository**:
   ```bash
git clone https://github.com/arsalan-ai-dev/Movie-Suggest.git
cd Movie-Suggest


