# Movie Recommendation System

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)  
![Flask](https://img.shields.io/badge/Flask-Backend-black?logo=flask)  
![HTML5](https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-orange?logo=html5)

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
  1. run `helper.py` first to create `user_item_matrix.csv`                
  2. then run `server.py` to active backend server                                 
  3. to run website navigate to the website's folder and open a command prompt terminal             
  4. in cmd type `python -m http.server` to expose HTTP on 8000 port     
  5. then run wesbite by typing `http://localhost:8000/` in browser

Note: Recommendation System will work only when there's 2 user in system

---

## 🌐 Backend API

- Endpoint	Method	Description  
    `/recommendation_system`  
    GET	Returns movie recommendation data

---

## ⚙ Helper utilities

- filter_movies() → Filters movies from the dataset based on given criteria

---

## 💻 Frontend behavior

- script.js → Uses PapaParse to parse CSV + stores likes/userID in localStorage
- genre.js → Same as above, specific to genre page
- movie.js → Parses CSV, manages likes, and fetches backend data

---

## 📊 Dataset
- imdb_top_1000.csv contains movie metadata used by the frontend
- Must remain in the same folder as the HTML/JS files

