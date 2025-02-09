# Gems of War API - Repository Description
🚀 Gems of War API is a complete API for real-time access to all Gems of War game data. This project aims to provide players and developers with structured and exploitable access to all the game's features.

## 📌 Features
* 📜 Troops, classes, weapons, pets
* 🏰 Realms, factions, underground
* ⚔️ Dungeons, arena, PvP, explorations
* 🎭 World events and guild events
* 🎯 Quests, challenges, adventure board
* 🏆 Advanced guild management (ranks, events, progression)
* 🔥 Soul forge, craftable items
* 📡 Automatic retrieval and real-time data update

## 🔧 Technology Stack
* Backend: `Node.js`, `Express.js`
* Database: `MongoDB` (or other configurable DB)
* Security: `Helmet`, `CORS`
* Logs: `Morgan`
* Deployment: `Docker` (optional)

## 📂 Project structure
* `/routes`: Defines all the routes API by category
* `/models` : Defines database schemas
* `/scripts` : Scripts to retrieve game data
* `/config` : Database and environment variable configuration

## 🚀 How to use it?

### Installation

```BASH
git clone https://github.com/votre-repo/gems-of-war-api.git
cd gems-of-war-api
npm install
```

### Configuration

Add a .env file with database connection variables

### Launch the API

```BASH
npm start
```

### Access Data

Examples:
* `GET /api/troops` → Troop List
* `GET /api/guilds` → Guild Details
* `GET /api/pvp` → PvP Info

🔗 Join the community and [contribute](https://docs.google.com/forms/d/e/1FAIpQLSfQz7br2jpt9mrkeI-dTJJWTft1ywtH5DW5FXZhYt-jne9Bvg/viewform?usp=dialog)! 🚀

📢 **Participate in discussions and improvements of the project!**
➡️ [Join the community on GitHub Discussions](https://github.com/CorentynDev/GoW-API/discussions)
