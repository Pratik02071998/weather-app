The weather application is a user-friendly, responsive, and intuitive React single-page application (SPA) designed to display real-time weather information for any city around the world. Developed using Microsoft Visual Studio, the app fetches live data from a weather API and allows users to search for current weather conditions, view key atmospheric details, and save their favorite locations for quick access.

Frontend Framework: React.js (with Hooks & functional components)
IDE: Microsoft Visual Studio
Styling: CSS Modules
API: OpenWeatherMap API (or any other public weather API)

1. City-Based Weather Search
Users can input the name of a city to fetch and display real-time weather information. On submission, the app makes an API call and renders data such as
Temperature (°C/°F)
Weather conditions (e.g., clear, cloudy, rainy)
Weather icons

2. Add to Favorites
After searching for a city, users can add that city to their Favorites list.
The Favorite Cities section is accessible on the main page
Clicking a favorite city instantly displays the latest weather for that location.

 3. Local Storage Integration
The Favorites list is stored in the browser's local storage, ensuring persistence across sessions.
This avoids the need for user login while maintaining a personalized experience.

4. Responsive Design
Fully optimized for desktop, tablet, and mobile devices.

5. Real-Time Data Refresh
Optional auto-refresh or manual refresh button to update weather details without reloading the entire page.
