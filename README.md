# 🌿 Eco Travel Mate – AI‑Powered Sustainable Travel Companion  
*Built under 48 hours for Green Spark Hackathon 2025*

[![Hackathon](https://img.shields.io/badge/Hackathon-Green%20Spark%202025-orange)](https://github.com/Christwin-Soy-Jose/eco-travel-mate)  
[![Platform](https://img.shields.io/badge/Platform‑Flutter‑%2B‑Firebase-blue)]  
[![License](https://img.shields.io/badge/License-MIT-green)]  

---

## 🎯 Problem Statement  
Short urban trips and unsustainable travel habits contribute significantly to emissions and health issues. Users often lack real-time feedback on their travel choices, making sustainable behavior hard to adopt.

---

## 🚀 Our Solution: Eco Travel Mate

A feature-rich mobile app that:
- Automatically tracks transportation and trip types  
- Calculates the carbon footprint of each journey  
- Provides real-time smarter travel suggestions  
- Gamifies sustainable habits with points, challenges, and dashboards  

---

## 🧩 Core Features

### **🚶‍♀️ Smart Travel Tracking**  
- Uses GPS + motion sensors to detect walking, cycling, driving, or public transport  
- Works passively—no manual input needed

### **♻️ Emissions Calculator**  
- Converts trip data into CO₂ output using trusted emission factors  
- Example:  
  - 2 km car ride → ~0.5 kg CO₂  
  - 2 km walk → zero emissions

### **🌿 Smarter-Choice Engine**  
Suggests greener alternatives post-trip:
> _“Your 2.3 km car ride emitted 0.5 kg CO₂. Cycling this route burns ~75 kcal and saves emissions—want to try next time?”_

### **🎮 GreenScore & Challenges**  
- Earn “GreenPoints” for eco-friendly travel choices  
- Weekly personalized challenges:  
  _“Swap two car trips with walking or cycling”_

### **👥 Community & Family Leadership**  
- Build teams or families  
- Compete in leaderboards  
- Foster peer motivation and local eco-awareness  

---

## 🧪 Tech Stack Overview

| Component       | Technologies Used                        |
|----------------|------------------------------------------|
| **Frontend**   | Flutter (Dart)                        |
| **Backend**    | Firebase (Auth, Firestore, Cloud Functions) or Flask |
| **AI / Logic** | Emission calculators & trip classifiers |
| **Location**   | GPS, Geolocator, Activity Recognition  |
| **Maps**       | Google Maps / Mapbox APIs              |
| **Gamification** | Points system, badges, notifications |

---

## 📦 Demo Structure & Screenshots

*(Add screenshots inside `assets/screenshots` and link below)*

| Feature UI          | Description                            |
|---------------------|----------------------------------------|
| Home Screen         | Shows GreenScore, recent trips, tips   |
| Trip Log            | Recent journey statistics + emissions  |
| Suggestion Popup    | After completing a drive trip          |
| Community Leaderboard | Family/team rankings                  |

---

## 🚀 Running the App Locally

```bash
git clone https://github.com/Christwin-Soy-Jose/eco-travel-mate.git
cd eco-travel-mate

flutter pub get

# Ensure Firebase CLI setup and config files (google-services.json or .env)
flutter run
