# movier_ecommender
# 🎥 Movie Recommender System

This is a content-based Movie Recommender System built using **Flask**, **HTML/CSS**, and **Python** libraries such as **NumPy**, **Pandas**, and **Scikit-learn**. It recommends 5 similar movies based on the one you select, using a similarity score derived from movie metadata.

---

## 🚀 Features

- Pick a movie and get 5 similar recommendations
- Uses cosine similarity on textual data (like genres, cast, keywords, etc.)
- Simple and interactive front-end built with HTML/CSS
- Powered by Flask as the backend web framework
- Includes 5000+ movies from the dataset

---

## 🛠️ Tech Stack

- **Python**
  - NumPy
  - Pandas
  - Scikit-learn
- **Flask**
- **HTML / CSS**
- **Pickle** (for loading precomputed similarity matrix)

---

## 🧠 How It Works

1. Movie data is cleaned and combined (genre, cast, keywords, etc.).
2. TF-IDF or CountVectorizer is used to convert text to numeric form.
3. Cosine similarity is calculated between all movie vectors.
4. When a user picks a movie, the system returns the 5 most similar movies.
