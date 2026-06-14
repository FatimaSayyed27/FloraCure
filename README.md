# 🌿 FloraCure — Rule Baesd Disease Expert System
FloraCure is a smart, web-based plant care assistant built with Django. It helps gardeners and plant lovers diagnose plant diseases from symptoms, get instant cure recommendations, track treatment history, and stay updated with live weather-based plant care tips — all in one place.
> *"Diagnose your plant, save your garden."*
---
## ✨ Key Features
### 🔐 User Authentication
- Secure Register, Login & Logout
- Profile management — update name, email, city, and password
### 🌱 Smart Plant Diagnosis
- Rule-based Expert System covering **30+ diseases** and **40+ symptoms**
- Upload plant photo + select symptoms
- Instant diagnosis with detailed cure recommendations
### 📊 Personal Dashboard
- Total Diagnoses
- Plants Tracked
- Active Treatments
- Cured This Month
### 🌤️ Live Weather Integration
- Auto-detects your location
- Real-time weather via OpenWeatherMap API
- Smart plant care tips based on current weather
### 📜 Diagnosis History
- View full diagnosis details
- Download professional PDF reports
- Mark plants as "Cured" to track recovery
### 📱 Fully Responsive
- Optimized for both desktop and mobile devices
---
## 🛠️ Tech Stack
| Layer | Technology |
|--------|-------------|
| Backend | Django (Python) |
| Frontend | HTML, Tailwind CSS |
| Database | SQLite |
| Weather API | OpenWeatherMap |
| PDF Reports | ReportLab |
---
## ⚙️ Getting Started
```bash
# 1. Clone the repository
git clone https://github.com/FatimaSayyed27/FloraCure.git
cd FloraCure
```
Visit `http://127.0.0.1:8000` in your browser 🌿
---
## 📁 Project Structure
```
FloraCure/
├── floraApp/           # Core app — models, views, urls
├── templates/           # HTML templates
├── static/               # CSS, images, icons
├── media/                # Uploaded plant images
├── manage.py
└── requirements.txt
```
---
## 🧠 How the Expert System Works
1. User selects a plant and checks symptoms (leaf, stem, root, pest, etc.)
2. The rule engine matches symptoms against a database of known diseases
3. Returns the matched disease and a tailored cure
4. Diagnosis is saved to history for future reference
**Categories covered:**
- 🍃 Leaf problems
- 🌿 Stem issues
- 🌱 Root problems
- 🌸 Flower & fruit issues
- 🐛 Pest infestations
- 🌡️ Environmental damage
---
## 🌤️ Weather-Based Plant Tips
FloraCure uses your device's location to fetch real-time weather and suggests care tips like:
- 🌧️ "Skip watering — rain expected"
- ☀️ "Water in the evening to avoid evaporation"
- 🌡️ "Hot day! Water early morning"
---
## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit a pull request.
## 📄 License
This project is open source and free to use for educational purposes.
---
<p align="center">Built with 💚 using Django & Tailwind CSS</p> 
