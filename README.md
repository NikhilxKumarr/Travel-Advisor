#  Travel Advisor APP

An intelligent travel guidance web app that helps users explore restaurants, hotels, and attractions based on location. Built with a responsive design and real-time data fetching to enhance user travel experiences.

## 🛠Tech Stack

- **React** (Frontend UI)
- **Material-UI** (Design system)
- **Google Maps API / Leaflet** (Geolocation and map rendering)
- **Travel Advisor API / RapidAPI** (Real-time location data and recommendations)
- **Axios** (API requests)
- **React Hooks + Context API** (State management and side effects)

##  Features

- 🔍Search for **restaurants**, **hotels**, and **attractions** based on user-selected location.
- Interactive **Google Maps** with location pins and info popups.
- 📱Fully responsive UI for both **mobile** and **desktop**.
-  Filter places by rating and type (e.g., fine dining, budget hotels).
-  Autocomplete search powered by Google Places API.
- Real-time data fetching from 3rd-party APIs.

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/NikhilxKumarr/Travel-Advisor.git
cd Travel-Advisor
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Environment Variables

Create a `.env` file in the root directory and add your API keys:

```env
REACT_APP_GOOGLE_MAPS_API_KEY=your_api_key_here
REACT_APP_TRAVEL_API_KEY=your_rapidapi_key_here
```

### 4. Run the App

```bash
npm start
```

Open http://localhost:3000 to view it in the browser.
