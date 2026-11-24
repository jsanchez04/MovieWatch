**MOVIEMATCH — PROTOTYPE RELEASE 
**
CONTENTS
- index.html: responsive MovieMatch dynamic web application with Matter.js physics poster wall, natural-language search, filter dropdowns, Surprise Me, optional TMDB poster integration, and IndexedDB watchlist CRUD.
- contribution_summary.txt: team contribution record for Assignment #4.
- demo_video_script.txt: 2 to 3 minute screen recording walkthrough script.

HOW TO RUN
- Online (Recommended): Open the deployed GitHub Pages URL in any modern desktop or mobile browser.
- Local: Extract the ZIP and open index.html in Chrome, Edge, Firefox, or Safari. (Internet connection enables the Matter.js CDN for the Physics Poster Wall; Grid View works completely offline.)

CORE FUNCTIONALITY (SRS ALIGNED)
- Natural-language mood search with required input validation and loading feedback (FR#1-FR#6, FR#26).
- Data controls: Genre, Release Era, Min Rating, and Sort By dropdown filters.
- Target 10-15 search results with Shuffle Results and Show All options (FR#8, FR#18).
- Interactive Matter.js Physics Poster Wall with drag/drop + Accessible Grid View toggle + Reduced Motion toggle (FR#20-FR#25, FR#39).
- "Surprise Me" random movie picker (FR#16).
- Movie detail modal with tags and one-click Watchlist save (FR#14).
- IndexedDB Database ("MovieMatchDB") with full CRUD:
  * CREATE: Save movies from Discover OR add a custom movie using the "+ Add Custom Movie" form.
  * READ: View saved movies, live stats, and status/priority filters (persists across browser refresh).
  * UPDATE: Toggle Watched status OR open the Edit modal to update Status, Priority, Personal Rating, and Notes.
  * DELETE: Remove entries with confirmation prompt.

OPTIONAL REAL MOVIE POSTERS (TMDB)
1. Click "Poster Setup (TMDB)" in the top navigation bar.
2. Paste a free TMDB API Read Access Token from https://www.themoviedb.org/settings/api
3. Click "Connect & Load Posters". The token stays in memory only and is never committed to GitHub.

ATTRIBUTION & DISCLAIMER
MovieMatch is a movie discovery prototype and does not host, stream, or guarantee streaming availability for full-length films.
TMDB Notice: "This product uses the TMDB API but is not endorsed or certified by TMDB."
