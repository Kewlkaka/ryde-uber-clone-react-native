# Ryde an Uber Clone 🚗

A modern, full-featured Uber clone built with React Native. This app replicates key features of Uber including real-time geolocation, authentication, ride requests, and more.

---

## 🛠 Tech Stack

- React Native
- Expo
- Serverless PostgreSQL
- Clerk
- Geoapify and Google Maps
- Zustand
- Tailwind CSS

---

## 🚀 Features

- **Onboarding**: Seamless user registration and setup process.
- **Email Password Auth with Verification**: Secure login with email verification via Clerk.
- **Home Screen with Live Location & Google Map**: Real-time location tracking with markers on a map.
- **Google Places Autocomplete**: Search any place with autocomplete suggestions.
- **Find Rides**: Search for rides by entering 'From' and 'To' locations.
- **Select Rides from Map**: Choose available cars near your location from the map.
- **Confirm Rides**: View complete ride details, including time and fare price.
- **Responsive on Android and iOS**: Optimized for both Android and iOS devices.

---

## 📱 Screenshots

Coming soon...

---

## 📦 Installation & Setup

To get the app up and running on your local machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/Kewlkaka/ryde-uber-clone-react-native.git
   cd ryde-uber-clone-react-native
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   - Create a `.env` file in the root directory and add your API keys for Google Maps, Clerk, and Neon Postgres.

   ```bash
   EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_api_key
   EXPO_PUBLIC_SERVER_URL=https://uber.com/
   EXPO_PUBLIC_GEOAPIFY_API_KEY=your_geoapify_key
   EXPO_PUBLIC_GOOGLE_API_KEY=your_google_maps_api_key
   DATABASE_URL=your_neon_postgres_url
   ```

4. Start the Expo development server:

   ```bash
   npx expo start
   ```

---

## ⚙️ Backend Setup (Neon Postgres)

This app uses Neon for a serverless PostgreSQL backend. You can set up your database using the following steps:

1. Go to [Neon](https://neon.tech/) and create a new serverless PostgreSQL database.
2. Update the database connection URL in your `.env` file as `DATABASE_URL`.
3. Migrate the database schema.

---

## 🤝 Contributing

Feel free to open issues or submit pull requests! Contributions, feedback, and suggestions are highly appreciated.

---
