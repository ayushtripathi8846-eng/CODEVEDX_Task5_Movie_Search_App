# 🎬 Cinemax

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Bebas+Neue&size=34&pause=1000&color=E84040&center=true&vCenter=true&width=900&lines=Premium+Movie+Discovery+Platform;Powered+by+TMDB+API;React+%2B+Tailwind+CSS+%2B+Framer+Motion;Search+%7C+Favorites+%7C+Infinite+Scrolling;Production+Ready+Frontend+Application" alt="Typing SVG" />

<br/>

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge\&logo=react)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3-38BDF8?style=for-the-badge\&logo=tailwindcss)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-Animations-0055FF?style=for-the-badge\&logo=framer)
![TMDB](https://img.shields.io/badge/TMDB-API-01D277?style=for-the-badge)
![Vite](https://img.shields.io/badge/Vite-Fast_Build-646CFF?style=for-the-badge\&logo=vite)

<br/>

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Now-e84040?style=for-the-badge)](https://search-movie-cinemax.netlify.app/)

### Discover • Search • Explore • Save Your Favorite Movies

*A premium movie discovery experience built with modern web technologies and cinematic UI design.*

</div>

---

# ✨ Overview

**Cinemax** is a modern movie discovery platform that delivers a smooth and immersive browsing experience using the TMDB API.

Designed with a premium glassmorphism interface, advanced search capabilities, beautiful animations, and responsive layouts, Cinemax helps users discover trending movies, explore detailed information, and save favorites effortlessly.

---

# 🚀 Live Demo

### 🌐 Live Demo

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge&logo=netlify)](https://search-movie-cinemax.netlify.app/)
---

# 📸 Preview

```txt
🎥 Trending Movies
🔎 Instant Search
❤️ Favorite Collection
🎬 Movie Details
👥 Cast Information
📺 Official Trailers
🎯 Similar Recommendations
♾️ Infinite Scrolling
```

---

# 🔥 Features

## 🎞 Hero Section

* Auto-rotating trending movies
* Dynamic background posters
* Smooth cinematic transitions
* CTA navigation buttons

---

## 🔍 Smart Search

### Real-Time Debounced Search

* Instant movie lookup
* Reduced API requests
* Search history persistence
* Keyboard-friendly interactions

---

## 🎯 Advanced Filters

Filter movies by:

* Genre
* Popularity
* Rating
* Release Year

Sort results dynamically for faster discovery.

---

## ♾ Infinite Scrolling

* Smooth content loading
* Intersection Observer API
* Seamless pagination
* Better user experience

---

## 🎬 Detailed Movie Pages

Each movie includes:

* Full overview
* High-resolution poster
* Rating information
* Runtime
* Genres
* Cast members
* Official trailers
* Similar movie recommendations

---

## ❤️ Favorites System

* Save favorite movies
* LocalStorage persistence
* Instant updates
* Dedicated favorites page

---

## ✨ Premium UI/UX

### Glassmorphism Design

* Frosted glass cards
* Blurred navigation
* Elegant shadows
* Modern dark aesthetics

### Smooth Animations

Powered by Framer Motion:

* Page transitions
* Hover effects
* Loading animations
* Component reveals

---

# 🛠 Tech Stack

| Technology      | Purpose            |
| --------------- | ------------------ |
| React 18        | Frontend Framework |
| React Router v6 | Routing            |
| Tailwind CSS v3 | Styling            |
| Framer Motion   | Animations         |
| Axios           | API Requests       |
| TMDB API        | Movie Data         |
| LocalStorage    | Persistence        |
| Vite            | Build Tool         |

---

# 🎨 Design System

## Colors

```css
Background: #0a0a0f
Primary: #e84040
Text: #ffffff
Muted: #9ca3af
Glass: rgba(255,255,255,0.05)
```

---

## Typography

### Display Font

```txt
Bebas Neue
```

### Body Font

```txt
DM Sans
```

---

# 📁 Project Structure

```bash
src/
│
├── components/
│   ├── layout/
│   │   ├── Navbar.jsx
│   │   └── Footer.jsx
│   │
│   └── ui/
│       ├── MovieCard.jsx
│       ├── SkeletonCard.jsx
│       ├── RatingBadge.jsx
│       ├── GenreTag.jsx
│       ├── FavoriteButton.jsx
│       ├── SearchBar.jsx
│       ├── Carousel.jsx
│       ├── EmptyState.jsx
│       └── InfiniteScroll.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── Search.jsx
│   ├── MovieDetail.jsx
│   ├── Favorites.jsx
│   └── NotFound.jsx
│
├── hooks/
│   ├── useDebounce.js
│   ├── useMovies.js
│   ├── useInfiniteMovies.js
│   ├── useFavorites.js
│   └── useSearchHistory.js
│
├── services/
│   ├── api.js
│   └── tmdb.js
│
├── context/
│   ├── FavoritesContext.jsx
│   └── SearchContext.jsx
│
├── App.jsx
├── main.jsx
└── index.css
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/cinemax.git

cd cinemax
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

## 3️⃣ Create Environment Variables

```bash
cp .env.example .env
```

Add your TMDB API key:

```env
VITE_TMDB_API_KEY=YOUR_API_KEY
```

---

## 4️⃣ Run Development Server

```bash
npm run dev
```

Application will start at:

```bash
http://localhost:5173
```

---

# 🔑 Getting TMDB API Key

1. Create an account at:

https://www.themoviedb.org

2. Navigate to:

```txt
Settings → API
```

3. Request a free API key

4. Add the key inside `.env`

---

# 📦 Production Build

Build optimized production files:

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

# 🚀 Deployment

Compatible with:

* Netlify
* Vercel
* Firebase Hosting
* GitHub Pages

Current Deployment:

```txt
Netlify
```

---

# 🌟 Performance Highlights

✅ Debounced Search

✅ Lazy Rendering

✅ Infinite Scroll

✅ Optimized API Calls

✅ Responsive Design

✅ Local Persistence

✅ Smooth Animations

✅ Clean Architecture

---

# 🔮 Future Improvements

* User Authentication
* Watchlist Feature
* Movie Reviews
* Dark / Light Theme Toggle
* AI Movie Recommendations
* Social Sharing
* Multi-language Support

---

# 🤝 Contributing

Contributions are welcome.

```bash
Fork the repository

Create a feature branch

Commit changes

Push to branch

Create Pull Request
```

---

# 📄 License

This project is licensed under the MIT License.

---

<div align="center">

### 🎬 Cinemax

Premium Movie Discovery Experience

Made with ❤️ using React, Tailwind CSS & TMDB API

<img src="https://readme-typing-svg.demolab.com?font=Bebas+Neue&size=24&pause=1000&color=E84040&center=true&vCenter=true&width=700&lines=Thanks+for+visiting+the+repository!;Star+the+project+if+you+like+it+⭐;Happy+Coding+🚀" />

⭐ Star this repository if you found it useful.

</div>
