# Movie Recommendation System

**A lightweight movie recommendation frontend with a small Flask backend.**

## 🚀 Features

- 🎬 Browse top movies from `imdb_top_1000.csv`
- 🏷 Genre tiles on the homepage
- 📽 Movie detail page with trailer (YouTube), rating, and overview
- ❤️ Like movies (saved to `localStorage` and sent to backend if logged in)
- 🔌 Simple Flask backend API

---

## 📂 File structure

recommendation system/
├─ index.html
├─ genre.html
├─ movie.html
├─ script.js
├─ genre.js
├─ movie.js
├─ style.css
├─ genre_style.css
├─ movie_style.css
├─ helper.py
├─ server.py
├─ imdb_top_1000.csv

---

## 📦 Requirements

- Python 3.8+
- Flask
- (Optional) Modern web browser

---

## 🛠 How to run locally

1️⃣ **Create a virtual environment**
```bash
python -m venv venv
# Activate:
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
