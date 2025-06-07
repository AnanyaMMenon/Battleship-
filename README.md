# 🚢 Battleships Game – Flutter + REST API

A mobile Battleships game built in **Flutter** that connects to a **RESTful API**. Players can register, log in, and play games against human or AI opponents, all in a responsive and user-friendly app.

---

## 🔧 Features

- ✅ User registration and login  
- 🔐 Session token management (with auto-expiry handling)  
- 🎮 Game list with matchmaking, active, and completed game states  
- 🚀 Play against humans or AI (random, perfect, or one-ship)  
- 🧠 Smart 5x5 ship placement interface  
- 💥 Turn-based gameplay with visual indicators for hits, misses, and sunk ships  
- 📱 Fully responsive layout for all screen sizes  

---

## 📲 How it Works

### 🔑 Authentication
- Register or log in to receive a token  
- Token is stored locally and used for API auth  
- Expired tokens require re-login  

### 🗂 Game List
- Shows active/matchmaking games by default  
- Toggle to view completed games  
- Refresh list manually  
- Tap a game to resume playing  
- Start a new game (vs human or AI)  
- Log out or forfeit a game  

### 🚢 New Game Setup
- Place 5 ships on a 5x5 grid  
- Tap to place/remove ships  
- Submit once all ships are placed  

### 🎮 Gameplay
- Visual indicators show:  
  - User ships  
  - Wrecked ships  
  - Missed shots  
  - Sunk enemy ships  
- Tap to take a shot if it's your turn  
- AI instantly responds in AI games  
- Refresh game state manually for human games  

---

## 🛠️ Tech Stack

- **Flutter**  
- **Dart**  
- **REST API** integration with `http`  
- **State management** with `provider`  
- **Local storage** with `shared_preferences`  

---

## 📦 API Base URL
https://battleships-app.onrender.com/

API provides endpoints for:

- Registering/logging in  
- Starting a game (vs human/AI)  
- Retrieving and updating game state  
- Playing shots and forfeiting games  

> Refer to `test.http` or Postman collection for sample API requests.

---
