# 🎬 React Movies App

A modern, responsive movie discovery app built with React and Vite. Search for movies, discover trending films, and explore cinema with a sleek, user-friendly interface.

## 🌟 Features

- **🔍 Smart Movie Search** - Search for movies with debounced input for optimal performance
- **📈 Trending Movies** - Display currently trending movies with real-time data
- **🎯 Movie Discovery** - Browse popular movies sorted by popularity
- **📱 Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **⚡ Fast Loading** - Built with Vite for lightning-fast development and builds
- **🎨 Modern UI** - Clean, intuitive interface with smooth animations
- **📊 Search Analytics** - Track popular searches with Appwrite integration

## 🌐 Live Demo

👉 [https://react-movies.aimaniskndr.my/](https://react-movies.aimaniskndr.my/)

## 🛠️ Quick Start

1. **Clone & Install**
   ```bash
   git clone https://github.com/aimaniskndr/react-movies.git
   cd react-movies
   npm install
   ```

2. **Environment Variables**

   Create a `.env` file in the root:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

## 🔧 Configuration

- **TMDB API:** [Get your API key](https://www.themoviedb.org/settings/api) and add to `.env`
- **Appwrite:** [Set up Appwrite](https://appwrite.io/), create a project/database/collection, and add IDs to `.env`
- **CORS:** Make sure your Appwrite project allows your local and deployed domains

## 🚀 Deployment

The app is live at [https://react-movies.aimaniskndr.my/](https://react-movies.aimaniskndr.my/)

To deploy your own:
- Build: `npm run build`
- Deploy the `dist` folder to Netlify, Vercel, or your preferred host

**[🎬 Try the Live Demo](https://react-movies.aimaniskndr.my/)**
