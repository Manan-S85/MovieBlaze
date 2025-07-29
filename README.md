# 🎬 MovieBlaze - React Movie Explorer with Appwrite

🚀 A blazing-fast React-based Movie Explorer that lets you search, discover, and trend your favorite movies from around the world — powered by **Appwrite** for backend and **TMDB API** for movie data.

<img width="1900" height="859" alt="image" src="https://github.com/user-attachments/assets/484c8f41-7b09-426c-8e14-17f9f874c122" />
 <!-- replace with actual screenshot -->

---

## 🧠 Features

- 🔍 **Search Any Movie** – Real-time search with support for multiple languages.
- 📈 **Trending Section** – Dynamically updates based on users' search history.
- 🎞️ **Movie Posters** – High-quality poster display for each movie.
- 🌐 **Language Tags** – Instantly know the original language of the movie.
- ⭐ **Ratings Display** – See how each movie ranks globally.
- 🧠 **Appwrite Integration** – Handles trending logic and user search data securely and efficiently.

---

## ⚙️ Tech Stack

| Frontend  | Backend / DB | API         |
|-----------|--------------|-------------|
| React.js  | Appwrite     | TMDB (The Movie DB) |

---

## 🖼️ Screenshots

> _Here's a sneak peek of what MovieBlaze looks like in action:_


<img width="1896" height="906" alt="image" src="https://github.com/user-attachments/assets/770b758e-e24f-4734-ab95-18b05f768a95" />
<img width="1901" height="355" alt="image" src="https://github.com/user-attachments/assets/8e5df22d-d34a-40b6-ad33-743cd3bfa06c" />
 


<h3>2. Install dependencies</h3>

```bash
npm install
```

<h3>3.Configure Appwrite

Create a .env file:</h3>

```bash
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

<h3>Start the development server</h3>

Start the development server

```bash
npm run dev
```

Visit: http://localhost:5173

<h3>🧠 How Trending Works</h3>

Every time a user searches for a movie, the search keyword is saved to Appwrite. Based on the frequency of these keywords, trending movies are dynamically updated — keeping your content fresh and user-driven!

<h3>🧠 Future Features</h3>

👤 User login & watchlists

💬 User reviews/comments

🎬 Genre-based filtering

🌙 Dark mode support

📲 Mobile-first PWA version

<h3>💻 Contributing</h3>

Pull requests are welcome! If you have ideas for new features or UI improvements, feel free to fork and contribute.


