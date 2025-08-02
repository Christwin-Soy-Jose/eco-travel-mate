# 🌿 Eco Travel Mate – AI-Powered Sustainable Travel Companion

> 🚀 Built in 48 hours for **Green Spark Hackathon 2025**

[![Hackathon](https://img.shields.io/badge/Hackathon-Green%20Spark%202025-orange)](https://github.com/Christwin-Soy-Jose/eco-travel-mate)
[![Platform](https://img.shields.io/badge/Platform-Flutter%20%2B%20Firebase-blue)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🎯 Problem Statement

Short-distance trips and unsustainable travel habits are significant contributors to carbon emissions and lifestyle diseases. Lack of awareness and real-time feedback make it difficult for individuals to shift toward greener choices.

---

## 🌱 Solution: Eco Travel Mate

**Eco Travel Mate** is a mobile app that:
- Automatically tracks user trips and transportation modes.
- Calculates carbon emissions in real-time.
- Provides greener travel suggestions.
- Uses gamification to encourage eco-friendly habits.

---

## 🧩 Core Features

### 🚶 Smart Travel Detection
Uses GPS and activity recognition to detect whether you’re walking, cycling, driving, or taking public transport — all without manual input.

### ♻️ CO₂ Emissions Calculator
Converts every trip into a carbon impact metric using trusted emission factors.

> ✅ Example: 2 km car trip = ~0.5 kg CO₂.  
> ✅ 2 km walk = 0 kg CO₂ and 75 kcal burned!

### 🌿 Greener Suggestion Engine
Suggests eco-friendly alternatives based on your route:

> *“You could have burned 75 kcal by cycling this 2.3 km trip and saved 0.5 kg CO₂.”*

### 🎮 GreenPoints & Challenges
- Earn **GreenPoints** for each eco-conscious action.
- Take on **weekly challenges** like:
  > “Swap 2 car trips with bike rides this week!”

### 👪 Community & Family Leaderboards
- Join family or friend groups.
- Compete based on GreenScores.
- Improve community-wide awareness through fun competition.

---

## 🛠 Tech Stack

| Layer             | Technology                                           |
|------------------|------------------------------------------------------|
| **Frontend**      | Flutter (Dart)                                       |
| **Backend**       | Firebase (Auth, Firestore, Cloud Functions), Flask  |
| **Location**      | GPS, Geolocator, Google Activity Recognition         |
| **AI & Logic**    | CO₂ emission calculator, travel-mode classifier      |
| **Mapping**       | Google Maps SDK / Mapbox                             |
| **Gamification**  | Custom points system, challenges, leaderboards       |

---

## 📱 Screenshots (Demo)

> Add your screenshots to the `assets/screenshots` folder and link them below.

| Feature              | Description                                   | Preview                                                  |
|----------------------|-----------------------------------------------|----------------------------------------------------------|
| 🏠 Home Screen        | GreenScore, trip summary, tips                | ![](assets/screenshots/home_screen.png)                  |
| 📊 Trip Log          | Detailed trip stats + carbon impact           | ![](assets/screenshots/trip_log.png)                     |
| 💡 Suggestion Popup  | Eco tip after non-green trip                  | ![](assets/screenshots/suggestion.png)                   |
| 🏆 Leaderboard       | Compare GreenScores across groups             | ![](assets/screenshots/leaderboard.png)                  |

---

## 🚀 Getting Started Locally

Clone and run the app on your local machine:

```bash
# 1. Clone this repo
git clone https://github.com/Christwin-Soy-Jose/eco-travel-mate.git
cd eco-travel-mate

# 2. Install dependencies
flutter pub get

# 3. Setup Firebase
# Add your google-services.json (Android) or GoogleService-Info.plist (iOS)

# 4. Run the app
flutter run
