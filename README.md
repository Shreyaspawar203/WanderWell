WanderWell: Your All-in-One Trip Planning Assistant
!<img width="1123" height="643" alt="image" src="https://github.com/user-attachments/assets/8d887bf4-88aa-4ba3-9236-bf6c47c4d9c2" />


📝 Overview
"WanderWell" is a dynamic and interactive web application designed to simplify the initial stages of trip planning. It provides a clean, centralized interface where users can research destinations, view stunning photos, check the weather, and convert currency, all in one place.

✨ Features
Destination Search: Search for any city in the world to get instant, relevant travel information.

Dynamic Background: The background image of the page changes with each search, providing an immersive visual experience.

Real-Time Weather: Displays the current temperature, weather conditions, and a 5-day forecast for your chosen destination.

Live Currency Converter: A practical tool that automatically converts currency based on the destination's location.

High-Quality Photos: A photo gallery populated with beautiful images from the Unsplash API to help you visualize your trip.

Recent Searches: The application remembers your most recent searches for quick and easy access.

🛠️ Technology Stack
This project is built using fundamental web technologies and relies on a few key APIs for dynamic content.

HTML5: For the core structure of the web page.

CSS3 (with Tailwind CSS): A utility-first framework used for modern, responsive, and mobile-first styling.

JavaScript: The main language for handling user interactions and fetching data from external APIs.

Unsplash API: Provides high-resolution, royalty-free images for the photo gallery and background.

OpenWeatherMap API: Delivers real-time and forecast weather data.

ExchangeRate-API: Supplies live currency exchange rates.

🚀 Getting Started
Prerequisites
You will need to obtain API keys from the following services. These are free and crucial for the application to function correctly.

Unsplash: Create a developer account to get your Access Key.

OpenWeatherMap: Sign up for a free account to get your API key.

ExchangeRate-API: Get a free API key from their website.

Installation
Clone or download the project files.

Open the travel_explorer.html file in a text editor like VS Code.

Locate the <script> tag at the bottom of the file.

Find the following lines and replace the placeholder text with your actual API keys:

const UNSPLASH_API_KEY = 'YOUR_UNSPLASH_API_KEY';
const OPENWEATHER_API_KEY = 'YOUR_OPENWEATHER_API_KEY';
const CURRENCY_API_KEY = 'YOUR_CURRENCY_API_KEY';

Save the file.

Open travel_explorer.html in your web browser to start using the application.

📄 License
This project is open-source and available under the MIT License.
