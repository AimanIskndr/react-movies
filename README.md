# 🎬 React Movies App

A modern, responsive movie discovery application built with React and Vite. Search for movies, discover trending films, and explore the world of cinema with a sleek, user-friendly interface.

## 🌟 Features

- **🔍 Smart Movie Search** - Search for movies with debounced input for optimal performance
- **📈 Trending Movies** - Display currently trending movies with real-time data
- **🎯 Movie Discovery** - Browse popular movies sorted by popularity
- **📱 Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **⚡ Fast Loading** - Built with Vite for lightning-fast development and builds
- **🎨 Modern UI** - Clean, intuitive interface with smooth animations
- **📊 Search Analytics** - Track popular searches with Appwrite integration

## 🚀 Live Demo

**[View Live App](https://react-movies.aimaniskndr.my/)**

## 🛠️ Tech Stack

- **Frontend Framework:** React 18
- **Build Tool:** Vite
- **Styling:** CSS3 with modern features
- **API Integration:** TMDB (The Movie Database) API
- **Backend Services:** Appwrite (for analytics)
- **State Management:** React Hooks (useState, useEffect)
- **Performance:** React-use (for debouncing)
- **Deployment:** Custom domain hosting

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/react-movies.git
   cd react-movies
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   VITE_TMDB_API_KEY=your_tmdb_api_key_here
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```

4. **Get your TMDB API Key**
   - Visit [TMDB API](https://www.themoviedb.org/settings/api)
   - Create an account and request an API key
   - Add the key to your `.env` file

5. **Set up Appwrite (Optional)**
   - Create an [Appwrite](https://appwrite.io/) account
   - Create a new project and database
   - Add your project details to the `.env` file

## 🏃‍♂️ Running the Application

### Development Mode
```bash
npm run dev
```
Visit `http://localhost:5174` to view the app in development mode.

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 📁 Project Structure

```
react-movies/
├── public/
│   ├── hero.png           # Hero banner image
│   └── vite.svg          # Vite logo
├── src/
│   ├── components/
│   │   ├── ErrorBoundary.jsx  # Error handling component
│   │   ├── MovieCard.jsx      # Individual movie card
│   │   ├── Search.jsx         # Search input component
│   │   └── Spinner.jsx        # Loading spinner
│   ├── App.jsx               # Main application component
│   ├── appwrite.js          # Appwrite configuration
│   ├── index.css           # Global styles
│   └── main.jsx            # Application entry point
├── .env                    # Environment variables
├── .gitignore             # Git ignore rules
└── README.md              # Project documentation
```

## 🎯 Key Features Explained

### Smart Search with Debouncing
- Implements 500ms debouncing to reduce API calls
- Real-time search results as you type
- Error handling for failed requests

### Movie Data Integration
- Fetches data from TMDB API
- Displays movie posters, titles, and details
- Handles both search results and popular movies

### Analytics Tracking
- Tracks popular search terms using Appwrite
- Stores most searched movies for trending analysis
- Helps understand user preferences

### Error Handling
- Comprehensive error boundaries
- User-friendly error messages
- Graceful fallbacks for API failures

## 🔧 Configuration

### TMDB API Setup
1. Create account at [TMDB](https://www.themoviedb.org/)
2. Go to Settings → API
3. Request an API key
4. Add to `.env` as `VITE_TMDB_API_KEY`

### Appwrite Setup (Optional)
1. Create account at [Appwrite](https://appwrite.io/)
2. Create new project
3. Set up database and collection
4. Configure CORS for your domain
5. Add credentials to `.env`

## 🌐 Deployment

The app is deployed at **[https://react-movies.aimaniskndr.my/](https://react-movies.aimaniskndr.my/)**

### Deploy Your Own Version

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Deploy the `dist` folder** to your hosting provider:
   - Netlify
   - Vercel
   - GitHub Pages
   - Custom hosting

3. **Configure environment variables** on your hosting platform

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [TMDB](https://www.themoviedb.org/) for providing the movie database API
- [Appwrite](https://appwrite.io/) for backend services
- [Vite](https://vitejs.dev/) for the amazing build tool
- [React](https://reactjs.org/) for the powerful frontend framework

## 🐛 Bug Reports & Feature Requests

If you encounter any bugs or have feature requests, please:
1. Check existing [issues](https://github.com/YOUR_USERNAME/react-movies/issues)
2. Create a new issue with detailed description
3. Include steps to reproduce (for bugs)

## 📊 Project Stats

- **React Version:** 18.x
- **Build Tool:** Vite 5.x
- **Bundle Size:** Optimized for performance
- **API Response Time:** ~200ms average
- **Mobile Responsive:** ✅ Fully responsive

---

Made with ❤️ by [Your Name](https://github.com/YOUR_USERNAME)

**[🎬 Try the Live Demo](https://react-movies.aimaniskndr.my/)**
