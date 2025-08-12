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
# run helper.py first to create user_item_matrix.csv                  |
# then run server.py to active server                                 |
# to run website go to the website's folder and type cmd              |
# in cmd type "python -m http.server" to expose HTTP on 8000 port     |
# then run wesbite by typing "http://localhost:8000/" in browser      |
# Recommended System will work only when there's 2 user in system 
