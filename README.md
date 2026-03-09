# AI Trip Planner 🌍✈️

AI Trip Planner is a smart web application that helps users generate personalized travel itineraries using Artificial Intelligence. Users can enter their destination, travel duration, budget, and number of travelers, and the system generates a complete trip plan including hotels, places to visit, and a daily itinerary.

This project was built using modern web technologies including **React, Vite, TailwindCSS, Firebase, and Google Gemini AI**.

---

## 🚀 Features

* 🔐 **Google Authentication** using Firebase
* 🧠 **AI-powered itinerary generation** using Gemini API
* 🏨 **Hotel suggestions** based on destination
* 📍 **Places to visit recommendations**
* 📅 **Day-wise travel plan**
* 💾 **Save trips to Firebase Firestore**
* 📊 **View previously created trips** in dashboard
* 🎨 Clean and responsive UI with TailwindCSS

---

## 🛠 Tech Stack

**Frontend**

* React.js
* Vite
* TailwindCSS
* React Router

**Backend / Services**

* Firebase Authentication
* Firebase Firestore Database

**AI Integration**

* Google Gemini API

**External APIs**

* Google Places API

---

## 📂 Project Structure

```
ai-trip-planner
│
├── public
│   └── images
│
├── src
│   ├── components
│   │   ├── custom
│   │   │   ├── Header.jsx
│   │   │   ├── Hero.jsx
│   │   │   └── Footer.jsx
│   │   └── ui
│   │
│   ├── create-trip
│   ├── view-trip
│   ├── my-trips
│   │
│   ├── service
│   │   ├── AiModel.js
│   │   └── GlobalApi.js
│   │
│   ├── config
│   │   └── FirebaseConfig.js
│   │
│   ├── constants
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .env
├── package.json
├── tailwind.config.js
└── vite.config.js
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/ai-trip-planner.git
```

### 2️⃣ Navigate to the project folder

```
cd ai-trip-planner
```

### 3️⃣ Install dependencies

```
npm install
```

### 4️⃣ Create `.env` file

Add your API keys:

```
VITE_GOOGLE_PLACE_API_KEY=your_google_places_api_key
VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_FIREBASE_API_KEY=your_firebase_api_key
```

### 5️⃣ Run the development server

```
npm run dev
```

Open in browser:

```
http://localhost:5173
```

---

## 🔑 API Keys Required

You need the following services:

* Google Gemini API
* Google Places API
* Firebase Project (Authentication + Firestore)

---

## 📸 Application Workflow

1. User logs in with Google account
2. User enters trip details (destination, days, budget, travelers)
3. Gemini AI generates a travel itinerary
4. Hotels and places are fetched using Google Places API
5. Trip details are saved in Firebase Firestore
6. User can view saved trips in the **My Trips dashboard**

---

## 🎯 Future Improvements

* Hotel booking system
* Payment gateway integration
* Map integration
* Travel cost estimation
* Admin dashboard
* User reviews and ratings

---

## 👨‍💻 Author

**Nishant**

Final Year Project – AI Powered Travel Planner

---

## 📄 License

This project is created for educational and learning purposes.
