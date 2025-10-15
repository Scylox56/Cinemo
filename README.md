# 🎬 Cinemo

A modern, glassmorphism-styled movie tracking application built with React. Search for movies, rate them, and keep track of what you've watched.

## ✨ Features

- **Real-time Movie Search** - Search through thousands of movies using the OMDB API
- **Movie Details** - View comprehensive information including plot, cast, director, and IMDb ratings
- **Personal Ratings** - Rate movies with an interactive star rating system
- **Watch List** - Track movies you've watched with your personal ratings
- **Statistics Dashboard** - View average ratings and total watch time
- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Modern UI** - Sleek glassmorphism design with GitHub-inspired dark theme

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to `http://localhost:5173`

## 🔑 API Key

This application uses the OMDB API for fetching movie data. The current API key is included in the code and will **expire in 365 days (1 year)**.

To get a new API key when it expires:

1. Visit [OMDB API](http://www.omdbapi.com/apikey.aspx)
2. Request a free API key
3. Replace the `KEY` constant in `App.jsx` with your new key

## 🎯 How to Use

1. **Search for Movies** - Type a movie title in the search bar (minimum 3 characters)
2. **View Details** - Click on any movie to see full details
3. **Rate Movies** - Use the star rating system to rate movies (1-10 stars)
4. **Add to List** - Click "Add to list" to save the movie to your watched list
5. **Remove Movies** - Click the X button on any watched movie to remove it
6. **Toggle Sections** - Use the +/- buttons to expand or collapse movie lists

## 🛠️ Built With

- React 18
- Vite
- CSS3 with Glassmorphism effects
- OMDB API

## 📱 Responsive Design

Cinemo is fully responsive and optimized for:

- Desktop computers
- Tablets
- Mobile phones

## 💡 Tips

- Press `Escape` to close movie details
- Your watched list is stored in the browser session
- Ratings are personal and saved locally

---

**Note:** This is a personal project for learning and demonstration purposes. Movie data and ratings are provided by OMDB and IMDb.
