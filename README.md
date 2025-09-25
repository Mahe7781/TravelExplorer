# 🌍 Travel Explorer ✈️

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)  
🔗 [Live Demo](https://mahe7781.github.io/TravelExplorer/)  
📂 [GitHub Repository](https://github.com/Mahe7781/TravelExplorer)

---

## 📖 Overview

**Travel Explorer** is a responsive, all-in-one travel planning website designed to simplify the trip planning process.  
Instead of switching between multiple fragmented platforms for weather, attractions, and hotels, users can access everything in one place through a **clean, intuitive, and mobile-responsive interface**.

---

## 🚩 Problem Statement

Trip planning is often **fragmented and time-consuming**:  
- Users need to manually gather information from different platforms (weather, attractions, hotels).  
- Existing travel websites are often **complex, expensive, or difficult to use**.  
- Travelers need a **centralized, simple, and responsive** platform.  

✅ **Solution**: Travel Explorer combines all essential travel information into one seamless application.

---

## ⭐ Features

- 🔎 **Smart Search** → Search any country or city for quick travel info.  
- 🌦️ **Real-time Weather** → Current conditions + 5-day forecast.  
- 🗺️ **Interactive Map** → Nearby attractions & hotels shown with Leaflet.js markers.  
- 📝 **Itinerary Planner** → Add attractions/hotels to a personal trip plan (saved in browser).  
- 📄 **PDF Export** → Download your trip plan as a PDF.  
- 📱 **Responsive Design** → Works on desktop, tablet, and mobile.  

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)  
- **CSS Framework**: Tailwind CSS  
- **JavaScript Libraries**:  
  - Leaflet.js → Interactive Maps  
  - jsPDF → PDF Generation  
- **External APIs**:  
  - OpenWeatherMap → Weather Data  
  - Unsplash → Destination Images  
  - Geoapify → Attractions & Hotels  
  - Frankfurter → Currency Exchange Rates  

---

## 📄 How It Works

1. **Homepage (`index.html`)** → Search bar + popular destinations.  
2. **Country Page (`country.html`)** → Displays top cities for the selected country.  
3. **Destination Page (`destination.html`)** → Weather, forecast, attractions, hotels with interactive map.  
4. **Planner Page (`planner.html`)** → Manage itinerary, save in localStorage, export as PDF.  

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Mahe7781/TravelExplorer.git
cd TravelExplorer
````

### 2. Configure API Keys

Replace the placeholder API keys in the JS files with your own:

* OpenWeatherMap
* Unsplash
* Geoapify
* Frankfurter

### 3. Run Locally

Open `index.html` in your web browser.

---

## ☁️ Deployment

The project is hosted using **GitHub Pages**.

* Simply push updates to the `main` branch, and the site is automatically deployed.
* 🔗 Live Site: [Travel Explorer](https://mahe7781.github.io/TravelExplorer/)

---

## 📊 Workflow

1. **Data Fetching** → APIs provide real-time data.
2. **Interactive Display** → Weather, maps, and attractions shown dynamically.
3. **Itinerary Planning** → Add/remove attractions & hotels, save to localStorage.
4. **Export & Deployment** → Download PDF itinerary, site hosted via GitHub Pages.

---

## 📈 Future Scope

* Backend integration (Node.js/Express + Database) for user accounts & saved itineraries.
* Secure payment gateway for hotel/flight bookings.
* AI-powered recommendation system for personalized travel suggestions.

---

## 📜 References

* [GitHub Docs](https://docs.github.com)
* [Tailwind CSS Docs](https://tailwindcss.com/docs)
* [Leaflet.js Reference](https://leafletjs.com/reference.html)
* [jsPDF Docs](https://artskydj.github.io/jsPDF/docs/)
* [OpenWeatherMap API](https://openweathermap.org/api)
* [Unsplash API](https://unsplash.com/developers)
* [Geoapify API](https://apidocs.geoapify.com)
* [Frankfurter API](https://www.frankfurter.app/docs)

---
