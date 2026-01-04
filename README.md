# 🎬 Movie Recommendation System

**Discover Your Next Favorite Movie · AI-Driven · Personalized Suggestions**

The Movie Recommendation System is a sophisticated machine learning application designed to provide personalized movie suggestions based on user preferences. By leveraging content-based filtering and data analytics, it creates a seamless and intuitive discovery experience for movie enthusiasts.

---

## 🔗 Live Demo & Video

- 🌐 **Live Application:** [http://localhost:8501](http://localhost:8501) *(Currently hosted locally)*
- 📂 **Repository:** [https://github.com/guptaakshat23/movie-recommendation-system-project](https://github.com/guptaakshat23/movie-recommendation-system-project)

---

## 🛠 Tech Stack

**Frontend & Interface**
- Streamlit
- Python

**Data & Machine Learning**
- Pandas
- Scikit-learn
- NumPy
- Pickle

**Deployment & Tooling**
- Heroku (Configuration ready)
- Git & GitHub

---

## 📑 Table of Contents

- [Overview](#overview)
- [Why This Project?](#why-this-project)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## 📖 Overview

This project aims to revolutionize the way users discover movies by solving the problem of choice paralysis. Using a dataset of over 5000 movies, the system analyzes movie attributes (such as genres, cast, and crew) to recommend films that are similar to a user's selected favorite.

The application is built with **Streamlit**, allowing for a responsive and interactive user interface that processes recommendations in real-time.

---

## ❓ Why This Project?

This recommendation engine was built to explore and demonstrate:

- **Content-Based Filtering:** Implementing algorithms that suggest items based on item attributes.
- **Data Preprocessing:** Cleaning and structuring complex datasets (TMDB 5000 movies).
- **Model Persistence:** Using `pickle` to serialize and load trained machine learning models efficiently.
- **Interactive UI:** Creating data-driven web applications using Streamlit.

---

## ✨ Key Features

- 🧠 **Recommendation Engine**
  Utilizes cosine similarity and content-based filtering to generate precise movie suggestions.

- 🔍 **Interactive Search**
  Select from thousands of movies to instantly get the top 5 most similar recommendations.

- ⚡ **Real-Time Processing**
  Optimized data handling ensures recommendations appear instantly upon request.

- 📊 **Rich Dataset**
  Built on the TMDB 5000 Movie Dataset, providing a wide array of film details.

---

## 🚀 Getting Started

Follow the steps below to run the Movie Recommendation System locally.

### ✅ Prerequisites

Ensure you have the following installed:

- Python 3.7+
- pip (Python Package Installer)

---

### 📥 Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/guptaakshat23/movie-recommendation-system-project.git](https://github.com/guptaakshat23/movie-recommendation-system-project.git)
   ```

2. **Navigate to the project directory**
   ```bash
   cd movie-recommendation-system-project
   ```

3. **Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Verify Data Files**
   Ensure `movie_dict.pkl` and `similarity.pkl` are present in the root directory (or generated via `Movie recommender system.py`).

---

## ▶️ Usage

Start the Streamlit development server:

```bash
streamlit run app.py
```

The application will automatically open in your browser at: `http://localhost:8501`

1. Select a movie from the dropdown menu.
2. Click the **Recommend** button.
3. View the top 5 recommended movies!

---

## 🗂 Project Structure

```text
movie-recommendation-system-project/
├── .gitignore
├── Procfile
├── README.md
├── app.py
├── requirements.txt
├── setup.sh
├── movie_dict.pkl
├── similarity.pkl (Ensure this exists)
├── Movie recommender system.py
├── tmdb_5000_credits.zip/
└── tmdb_5000_movies.zip/
```

---

## 🔮 Future Enhancements

- ☁️ **Cloud Deployment:** Fully deploy the application to Heroku or AWS.
- 🖼️ **Movie Posters:** Fetch and display official movie posters using the TMDB API.
- 📈 **Trending Section:** Add a section for currently popular or top-rated movies.
- 🤝 **Hybrid Filtering:** Combine content-based filtering with collaborative filtering for better accuracy.

---

## 📄 License

This project is open-source and available for educational purposes.

⭐ **If you find this project useful or interesting, consider giving it a star on GitHub!**
