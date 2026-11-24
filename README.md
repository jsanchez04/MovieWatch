# 🎬 MovieMatch — Application Design Prototype
**Less scrolling. More watching.**

MovieMatch is a dynamic movie discovery web application built for Towson University's Software Engineering course. It reduces streaming decision fatigue by combining natural-language mood search, an interactive **Matter.js** physics poster wall, and a persistent **IndexedDB** watchlist.

🌐 **Live Demo:** https://jsanchez04.github.io/MovieWatch/

---

## ✨ Key Features (SRS Aligned)

| Feature | Description | SRS Alignment |
| :--- | :--- | :--- |
| **Natural-Language Search** | Describe a mood, genre, or vibe (e.g., *"funny mystery with a twist"*) with required-field validation and loading feedback. | FR#1–FR#6, FR#26 |
| **Smart Data Controls** | Filter and sort results by **Genre**, **Release Era**, **Minimum Rating**, and **Sort Order**. | Rubric Data Controls |
| **Interactive Physics Wall** | Drag, toss, and stack up to 15 movie posters using **Matter.js**, with an **Accessible Grid View** and **Reduced Motion** toggle. | FR#8, FR#20–FR#25, FR#39 |
| **Surprise Me & Shuffle** | Instantly highlight and open a random movie pick or shuffle the current results. | FR#16, FR#18 |
| **Movie Details Modal** | View synopsis, release year, genre, rating, mood tags, and one-click Watchlist saving. | FR#14 |
| **IndexedDB Watchlist (CRUD)** | Persistent browser database (`MovieMatchDB`) supporting full Create, Read, Update, and Delete operations. | Database Requirement |

---

## 🗄️ Database Operations (`MovieMatchDB`)
* **Create:** Save movies from the Discover page or click **+ Add Custom Movie** to add a new record via form validation.
* **Read:** View saved movies, live counters, and status/priority filters (persists across page refreshes).
* **Update:** Toggle **Mark Watched** or open the **Edit** modal to change Status, Priority, Personal Rating, and Notes.
* **Delete:** Remove saved entries with a confirmation prompt.

---

## 🚀 How to Run
1. **Online (Recommended):** Open the live link at https://jsanchez04.github.io/MovieWatch/ in any modern desktop or mobile browser.
2. **Locally:** Download or extract the project files and open `index.html` in Chrome, Edge, Firefox, or Safari. *(An internet connection loads Matter.js for the Physics Wall; Grid View works offline.)*

### Optional: Load Live Movie Posters (TMDB)
1. Click **Poster Setup (TMDB)** in the top navigation bar.
2. Paste a free **TMDB API Read Access Token** from [TMDB API Settings](https://www.themoviedb.org/settings/api).
3. Click **Connect & Load Posters**. *(Your token stays in memory only and is never stored or committed to GitHub.)*

---

## 👥 Team
* **Raphael Olatunde**
* **Jeremiah Sanchez**
* **Onyinye Ojiako**

---

> **Disclaimer & Attribution:** MovieMatch is an educational movie discovery prototype and does not host, stream, or guarantee streaming availability for full-length films.  
> *This product uses the TMDB API but is not endorsed or certified by TMDB.*
