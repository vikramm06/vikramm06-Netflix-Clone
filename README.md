# Netflix Clone

🔗 Live Demo: [Netlify](https://binge-watch-movie.netlify.app) 

A fully functional Netflix clone built using modern web technologies. This project features user authentication, a dynamic movie database integration, and a responsive design that mimics the original Netflix experience.

## 🔑 Key Features

- **Dynamic Content:** Seamlessly fetches trending, popular, and top-rated movies using the **TMDB API**.
- **User Authentication:** Robust sign-up and login flow powered by **Firebase Auth**.
- **API Testing:** Used **Postman** to test and document API endpoints for reliable data handling.
- **Interactive UI:** Features a sleek video player, custom hover effects, and a dynamic navbar.
- **Optimized Performance:** Built with **Vite** for lightning-fast load times and smooth transitions.

## 🛠️ Tech Stack

- **Frontend:** React.js, HTML5, CSS3 (Custom Modules)
- **State Management:** React Hooks (useState, useEffect)
- **Backend/Auth:** Firebase
- **Data Fetching:** Axios / TMDB API
- **Tooling:** Vite, NPM, Postman (API Testing)
- **Deployment:** Netlify

## 🏁 Development Setup

### Prerequisites
- Node.js (Latest version)
- A TMDB API Key

### Installation

1. **Clone the Repo:**
   ```bash
   git clone https://github.com
   cd Netflix-Clone
   ```

2. **Install Packages:**
   ```bash
   npm install
   ```

3. **Env Configuration:**
   Create a `.env` file and add your credentials:
   ```env
   VITE_FIREBASE_API_KEY=your_firebase_key
   VITE_TMDB_API_KEY=your_tmdb_key
   ```

4. **Start Development:**
   ```bash
   npm run dev
   ```

## 🌐 Deployment & Testing

- **Hosting:** This project is continuously deployed via **Netlify**, connected directly to the `main` branch.
- **API Verification:** All TMDB endpoints were verified and tested using **Postman** collections to ensure data structure integrity before integration.

---
<p align="center"><b>Developed by <a href="https://github.com/Lakshmi759">Lakshmi</a></b></p>
