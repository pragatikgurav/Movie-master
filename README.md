# 🎬 Movie Master

> A modern movie discovery web application built with **Next.js, TypeScript, Tailwind CSS, and the OMDb API**.

## 🌟 Overview

**Movie Master** is a responsive movie discovery application that allows users to explore movies, search for specific titles, view movie information, and interact with a modern movie-focused interface.

The application uses the **OMDb API** to retrieve movie information dynamically and presents the data through a clean and responsive user interface.

---

## ✨ Features

* 🎬 Browse movie content
* 🔍 Search movies by title
* 📝 View movie information
* 🖼️ Display movie posters
* 🎞️ Movie video/player interface
* 📱 Fully responsive design
* ⚡ Fast Next.js application
* 🎨 Modern Tailwind CSS interface
* 🌐 Real-time movie data using OMDb API
* 🧩 Reusable React components
* ❌ Placeholder poster support when movie artwork is unavailable

---

## 🛠️ Technologies Used

| Technology   | Purpose                                   |
| ------------ | ----------------------------------------- |
| Next.js      | React framework and application structure |
| React        | Building the user interface               |
| TypeScript   | Type-safe JavaScript development          |
| Tailwind CSS | Styling and responsive UI                 |
| OMDb API     | Fetching movie information                |
| JavaScript   | Application logic                         |
| HTML5        | Web page structure                        |
| CSS3         | Styling                                   |
| Git          | Version control                           |
| GitHub       | Source code hosting                       |

---

## 📂 Project Structure

```text
Movie-master/
│
├── public/
│   └── placeholder-poster.svg
│
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── search/
│   │       └── page.tsx
│   │
│   ├── components/
│   │   ├── HeroBillboard.tsx
│   │   ├── MoviePageClient.tsx
│   │   ├── MovieRow.tsx
│   │   ├── Navbar.tsx
│   │   ├── SearchPageClient.tsx
│   │   └── VideoPlayer.tsx
│   │
│   └── lib/
│       └── omdb.ts
│
├── .env.local.example
├── .gitignore
├── next.config.js
├── package.json
├── postcss.config.mjs
├── tailwind.config.ts
├── tsconfig.json
└── README.md
```

---

## 🔑 API Configuration

This project uses the **OMDb API** to retrieve movie information.

Create a file named:

```text
.env.local
```

Add your API key:

```env
NEXT_PUBLIC_OMDB_API_KEY=your_omdb_api_key_here
```

### Important

Never upload `.env.local` to GitHub because it contains your API key.

The project includes `.env.local.example` as a safe template.

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Movie-master.git
```

### 2. Open the project

```bash
cd Movie-master
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure the API key

Create:

```text
.env.local
```

and add:

```env
NEXT_PUBLIC_OMDB_API_KEY=your_omdb_api_key_here
```

### 5. Start the development server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

## 📦 Available Commands

### Start development server

```bash
npm run dev
```

### Create production build

```bash
npm run build
```

### Start production server

```bash
npm start
```

### Run lint

```bash
npm run lint
```

---

## 🔄 How the Application Works

```text
User
  ↓
Movie Master UI
  ↓
Search / Browse Movies
  ↓
React Components
  ↓
OMDb API
  ↓
Movie Data
  ↓
Movie Cards / Details
  ↓
User Interface
```

### Step-by-step

1. The user opens the Movie Master application.
2. The user searches for a movie or browses the available content.
3. React components handle the user interaction.
4. The application sends a request to the OMDb API.
5. OMDb returns movie information.
6. The application processes the response.
7. Movie information and posters are displayed on the screen.
8. If a poster is unavailable, a placeholder image is displayed.

---

## 🎯 Main Components

### `Navbar.tsx`

Handles the application's navigation and search-related interface.

### `HeroBillboard.tsx`

Displays the main movie/banner section of the application.

### `MovieRow.tsx`

Displays movie content in reusable rows/cards.

### `SearchPageClient.tsx`

Handles movie search functionality and displays search results.

### `MoviePageClient.tsx`

Handles movie-specific information and page content.

### `VideoPlayer.tsx`

Provides the movie/video player interface.

### `omdb.ts`

Contains the OMDb API-related functionality used to retrieve movie information.

---

## 📱 Responsive Design

Movie Master is designed to work across different screen sizes:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📱 Tablet

Tailwind CSS responsive utilities are used to create the responsive interface.

---

## 🔐 Security

The project uses environment variables for API configuration.

Do not commit:

```text
.env
.env.local
.env.production
```

The `.gitignore` file prevents these files from being uploaded accidentally.

---

## 🔮 Future Enhancements

Possible improvements include:

* ⭐ User ratings and reviews
* ❤️ Favorites/watchlist
* 👤 User authentication
* 🎭 Genre-based filtering
* 📅 Upcoming movie section
* 🔥 Trending movies
* 🎬 Trailer integration
* 📜 Search history
* 🌙 Dark/light theme
* ☁️ Cloud database integration
* 🚀 Deployment with Vercel

---

## 👩‍💻 Developer

**Pragati Gurav**

🎓 B.E. Computer Science Engineering — 2026 Graduate

💻 Java Full Stack Developer

### GitHub

https://github.com/pragatikgurav

---

## 📄 License

This project is created for educational and portfolio purposes.

Movie information is provided through the OMDb API.

---

⭐ If you find this project useful, consider giving the repository a star!
