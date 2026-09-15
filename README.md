# Movie Genre Tracker 🎬

A modern, responsive single-page web application to track movies by genre, discover streaming availability across OTT platforms (Netflix, Prime Video, Disney+ Hotstar, Apple TV+, etc.), and manage fallback/alternative streaming and search links.

## ✨ Features

- **Dynamic Genre Tabs & Badges**: Filter effortlessly across Action, Sci-Fi, Thriller, Comedy, Drama, Horror, Animation, and custom genres with real-time movie counts.
- **OTT Streaming & Fallback Links**:
  - Direct 1-click button to primary streaming platform.
  - Fallback / Alternative Stream link (e.g. YouTube search, Google stream lookup).
- **Add / Edit Movie Modal**: Full form with title, genre, OTT platform, direct links, fallback search shortcuts, rating, release year, poster image, and synopsis.
- **Watchlist & Status Management**: Quick 1-click toggle between *Want to Watch* and *Watched*.
- **Search & Advanced Sort**: Live search by keyword, filter by OTT platform/status, and sort by highest rated, newest release, or title.
- **Browser LocalStorage Persistence**: Stores and loads entries locally in browser storage, pre-loaded with sample movies.
- **Export Backup**: One-click JSON data export.
- **Glassmorphism & Cinematic UI**: Built with Tailwind CSS and Lucide icons for a sleek dark mode interface.

## 🚀 Quick Start

Open `index.html` directly in any web browser, or run a local web server:

```bash
# Using Python
python3 -m http.server 8080

# Or using npx serve
npx serve .
```

Then visit `http://localhost:8080`.
