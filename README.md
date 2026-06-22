# 🎬 Movie Recommendation System

A Machine Learning project that recommends movies similar to a selected movie using Content-Based Filtering. The recommendation engine analyzes movie metadata such as genres, keywords, cast, and crew information to suggest relevant movies.

---

## 📌 Project Overview

This project builds a movie recommendation system using the TMDB 5000 Movies Dataset. By combining multiple movie attributes and applying Natural Language Processing (NLP) techniques, the system identifies movies with similar characteristics and generates recommendations.

---

## ✨ Features

- Content-Based Movie Recommendation
- Similar Movie Suggestions
- Data Cleaning and Preprocessing
- Feature Engineering
- NLP-Based Text Processing
- Cosine Similarity Calculation
- Efficient Recommendation Retrieval

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- NLTK
- Jupyter Notebook

---

## 📂 Project Structure

```text
Movie_Recommendation/
│
├── Movie_Recommender.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
└── README.md
```

---

## 📊 Dataset

The project uses the TMDB 5000 Movies Dataset containing:

- Movie Titles
- Genres
- Keywords
- Cast Information
- Crew Information
- Movie Overview

Files:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

---

## ⚙️ Methodology

### 1. Data Collection

The movie and credits datasets are loaded and merged.

### 2. Data Preprocessing

- Handling missing values
- Selecting useful features
- Cleaning text data

### 3. Feature Engineering

Relevant movie attributes such as genres, keywords, cast, crew, and overview are combined into a single feature representation.

### 4. Text Vectorization

The combined textual features are converted into vectors using NLP techniques.

### 5. Similarity Computation

Cosine Similarity is used to measure similarity between movies.

### 6. Recommendation Generation

For a selected movie, the system retrieves the most similar movies based on similarity scores.

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/guptaansh97100/Movie_recommendation-.git
```

### Move to Project Directory

```bash
cd Movie_recommendation-
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn nltk
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Movie_Recommender.ipynb` and run all cells.

---

## 📈 Results

The recommendation system successfully identifies movies with similar content and provides relevant recommendations based on movie characteristics rather than user ratings.

---

## 🎯 Future Improvements

- Collaborative Filtering
- Hybrid Recommendation System
- Movie Poster Integration
- Real-Time Movie API Support
- Web-Based User Interface

---

## 📚 Key Learning Outcomes

- Data Cleaning and Preprocessing
- Feature Engineering
- Natural Language Processing
- Recommendation Systems
- Cosine Similarity
- Machine Learning Workflow

---

## 👨‍💻 Author

**Ansh Gupta**

GitHub: https://github.com/guptaansh97100

---

⭐ If you found this project useful, consider giving it a star.
