# 🌍 GeoLearm

**GeoLearn** is an interactive web application that helps users learn about the geography of India through map-based quizzes, user profiles, and real-time scoring. Built using HTML, CSS, JavaScript, Firebase, and Leaflet.js, the platform offers a gamified learning experience with state-specific quizzes and a personalized dashboard.

---

## 🚀 Features

- 🗺️ **Interactive Map**  
  Explore an India map with clickable states powered by Leaflet.js.

- 🧠 **Statewise Quizzes**  
  Take multiple-choice quizzes for each Indian state and union territory.

- 🔐 **User Authentication**  
  Sign up, log in, and track your progress using Firebase Authentication.

- 👤 **User Profiles**  
  View scores, rewards, and visited states on your personal profile page.

- 📊 **Score Tracking**  
  Real-time score updates stored in Firebase Realtime Database.

- 🛡️ **Attempt Restriction**  
  Prevents repeated attempts from inflating your score unfairly.

---

## 📁 Project Structure
GeoLearn/
│

├── index.html # Homepage with the India map

├── login.html # User login/signup page

├── profile.html # User profile showing progress

├── quiz.html # Dynamic quiz loader for states

├── /p1/images/ # User avatars and other assets

├── firebase.js # Firebase config and setup

├── style.css # Global styles


├── README.md # You're here!




---

## 🔧 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript  
- **Backend & Auth:** Firebase Authentication, Firebase Realtime Database  
- **Map API:** Leaflet.js  
- **Deployment:** Local Server

---

## 🧩 How It Works

1. User signs up/logs in using Firebase Authentication.  
2. Homepage (`index.html`) shows a Leaflet-powered map of India.  
3. Clicking a state opens `quiz.html` with that state’s questions pulled from Firebase.  
4. Scores are stored and updated in Firebase in real-time.  
5. `profile.html` displays email, total score, and statewise progress.

---




