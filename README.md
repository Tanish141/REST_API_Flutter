Flickd - Flutter Movie App 🚀
Flickd is a sleek and modern Flutter application that uses REST APIs to fetch and display movie data. The app provides users with an engaging experience to browse movies, check details, and search by categories.

🌟 Features
REST API Integration: Fetches real-time movie data using a RESTful API.
Dynamic UI: Displays movie details such as posters, ratings, descriptions, and release dates.
Search Functionality: Search movies by text or category (e.g., Popular, Upcoming).
Responsive Design: Optimized for different screen sizes, ensuring a smooth experience on all devices.
Blurry Backgrounds: Uses the movie poster as a blurred background for aesthetic appeal.
Efficient Performance: Lazy-loading ensures smooth scrolling and reduces resource usage.

🛠️ Technologies Used
Flutter: For building the app's UI and functionality.
Riverpod: State management for efficient and clean architecture.
Dart: Language powering the app.
REST API: To retrieve data from a movie database.
Material Design: For a modern and polished look.

📦 Packages Used
flutter_riverpod: For state management.
http: For making REST API calls.
flutter/material.dart: For UI components and theming.


🚀 Getting Started
1. Prerequisites
Install Flutter and ensure your environment is set up.
Obtain an API key from the movie database API provider (e.g., TMDB).
2. Clone the Repository
git clone https://github.com/your-username/flickd-rest-api-app.git
cd flickd-rest-api-app
3. Add API Key
Replace YOUR_API_KEY in the lib/config/api_config.dart file with your actual API key.
const String API_KEY = "YOUR_API_KEY";
const String BASE_URL = "https://api.themoviedb.org/3";
4. Run the App
flutter pub get
flutter run

📂 Folder Structure
lib/
models/: Data models for movies and categories.
widgets/: Reusable UI components like movie tiles.
controllers/: Logic for fetching data and managing state.
views/: Main UI screens (e.g., Home Page).
config/: API configuration.

✨ Future Improvements
Add a "Favorite Movies" feature.
Implement user authentication for personalized recommendations.
Include more categories and filters.
Enable offline viewing using cached data.

🤝 Contributions
Contributions are welcome! Feel free to submit a pull request or open an issue for bugs and feature suggestions.

🙏 Acknowledgments
TMDB API for movie data.
The Flutter and Dart community for guidance and support.
