# The Legacy Glide

 *A Spigot plugin recreating the Glide minigame, developed by Darkmoon Studios.*  

![GitHub](https://img.shields.io/github/license/WatermanMC/TheLegacyGlide?color=blue)  
![Spigot](https://img.shields.io/badge/Spigot-1.8--1.20-success)  

---

## 📖 Overview  
This plugin brings the **Glide minigame** to Minecraft servers, where players navigate through obstacle courses to reach the bottom safely. Features include customizable maps, Elytra mechanics, timed leaderboards, and multiplayer support.

---

## ✨ Features  
✅ **Multi-Arena Support** – Run multiple games simultaneously.  
✅ **Customizable Courses** – Import or generate maps via config.  
✅ **Elytra Mechanics** – Optional gliding with tweakable physics.  
✅ **Scoreboards & Leaderboards** – Track wins, times, and records.  
✅ **Rewards System** – Integrates with Vault for in-game prizes.  
✅ **Optimized Performance** – Lightweight and lag-free.  

---
## Requirements
1. [Vault plugin](https://www.spigotmc.org/resources/vault.34315/).
2. Java 8 or higher
3. Minecraft version 1.13+

## ⚙️ Installation  
1. Download the latest `.jar` from [Releases](https://github.com/<username>/<repo>/releases).  
2. Place it in your server’s `plugins/` folder.  
3. Restart the server.  
4. Configure `plugins/Glide/config.yml` (auto-generated on first run).  

---

## 🎮 Commands  
| Command | Description | Permission |
|---------|-------------|------------|
| `/glide join <arena>` | Join a game | `glide.player` |
| `/glide leave` | Quit a game | `glide.player` |
| `/glide admin create <arena>` | Create an arena | `glide.admin` |

---

## 📂 Configuration  
Edit `config.yml` to:  
- Set course boundaries.  
- Toggle Elytra usage.  
- Customize rewards.  

Example:  
```yaml
arenas:
  sky_glide:
    spawn: x, y, z, world
    elytra: true
    reward: 100
