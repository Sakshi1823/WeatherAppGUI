<h1 align="center">☁️ WeatherAppGUI</h1>

<p align="center">
  <b>Java desktop application that fetches and displays live weather data through a clean Swing GUI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java%20Swing-GUI-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/JSON%20Simple-Library-lightgrey?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white"/>
</p>

---

## What This Does

WeatherAppGUI is a desktop Java application built with **Java Swing/AWT** that fetches real-time weather data and presents it through a clean, user-friendly graphical interface. It demonstrates core Java OOP principles, GUI component design, external API consumption, and JSON parsing — all without a web browser.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Java |
| GUI Framework | Java Swing / AWT |
| Data Parsing | JSON Simple Library |
| Weather Data | Live weather API |
| IDE | IntelliJ IDEA / VS Code |

---

## ✨ Features

- Fetches **live weather data** via external API
- Clean, responsive desktop GUI built with Java Swing
- JSON response parsing with JSON Simple library
- Organized MVC-style project structure
- Runs as a standalone desktop application — no browser needed

---

## 📂 Project Structure

```
WeatherAppGUI/
└── WeatherAppGUI/
    └── src/
        ├── AppLauncher.java       # Entry point
        ├── WeatherAppGui.java     # Main GUI window
        ├── WeatherApp.java        # API call + data logic
        └── [assets/images]
```

---

## 🏃 Run Locally

```bash
git clone https://github.com/Sakshi1823/WeatherAppGUI.git
cd WeatherAppGUI
# Open in IntelliJ IDEA or VS Code with Java extension
# Add JSON Simple library to your classpath (or via Maven/Gradle)
# Run AppLauncher.java
```

> Make sure you have **JDK 11+** installed.

---

## 🚀 Roadmap

- [ ] Add 5-day forecast view
- [ ] City search with autocomplete
- [ ] Dark/light theme toggle
- [ ] Package as executable `.jar` for easy distribution

---

<p align="center">Built by <a href="https://github.com/Sakshi1823">Sakshi Hingamire</a> </p>
