````markdown
# 🎬 Movie Search App — React + Appwrite

A simple and responsive **movie search application** built using **React** for the frontend and **Appwrite** for backend services. This app allows users to:

- 🔥 View trending movies  
- 🔍 Search for any movie by title  
- 🎨 Enjoy a clean, modern UI without the need to log in  

> **Live Demo:** [Visit the website](https://lightgoldenrodyellow-alpaca-242021.hostingersite.com/)

---

## 📌 Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Screenshots](#screenshots)  
- [Setup Instructions](#setup-instructions)  
- [Folder Structure](#folder-structure)  
- [Future Improvements](#future-improvements)  
- [License](#license)  
- [Author](#author)

---

## ✅ Features

- **Trending Movies**: Displays a curated list of trending movies on page load  
- **Search Functionality**: Live search to explore movie titles  
- **Responsive Design**: Works well across devices  
- **No Authentication**: Public access, no login required  
- **Fast and Lightweight**: Built using React with minimal dependencies  

---

## 🛠 Tech Stack

| Layer       | Technology                |
|-------------|---------------------------|
| Frontend    | React.js, CSS             |
| Backend     | Appwrite (Cloud/Self-hosted) |
| Movie API   | TMDB or similar movie API |
| Hosting     | Hostinger                 |

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-search-app.git
cd movie-search-app
````

### 2. Install Dependencies

Make sure Node.js and npm are installed, then run:

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root folder and add the following:

```env
VITE_TMDB_API_KEY=YOUR_TMDB_API_KEY
VITE_APPWRITE_PROJECT_ID=YOUR_PROJECT_ID
VITE_APPWRITE_DATABASE_ID=YOUR_DATABASE_ID
VITE_APPWRITE_COLLECTION_ID=YOUR_COLLECTION_ID
```

> ✅ This app does **not** require login — Appwrite collections should be public or allow anonymous read access.

### 4. Start the Development Server

```bash
npm start
```

Visit the app at [http://localhost:5173](http://localhost:5173)

---

## 📁 Folder Structure

```text
src/
├── assets/           # Static Assets
├── components/       # UI components (MovieCard, SearchBar, etc.)
├── appwrite.js       # API interaction logic (Appwrite & Movie API)
├── App.jsx           # Root component
└── main.jsx          # Application entry point
```

---

## 🌱 Future Improvements

* [ ] Infinite scrolling or pagination
* [ ] Movie detail page with additional metadata
* [ ] Dark mode support
* [ ] Loading and error states
* [ ] CI/CD deployment pipeline

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Shubham Aggarwal**
[GitHub](https://github.com/shubhamagg) • [LinkedIn](https://www.linkedin.com/in/shubham-aggarwal/)

---

## 🙌 Acknowledgements

* [React](https://reactjs.org/)
* [Appwrite](https://appwrite.io/)
* [TMDB API](https://www.themoviedb.org/documentation/api)
* [Hostinger](https://www.hostinger.com/)

```
