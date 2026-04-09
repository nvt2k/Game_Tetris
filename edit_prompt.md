```markdown id="p8x4k2"
# 🎮 Prompt: Build an Advanced Neon Tetris Game (Web-Based)

## 🧠 Role
You are a senior game developer and frontend engineer. Your task is to build a polished, high-performance Tetris game with modern visuals, animations, sound, and persistent data.

---

## 🎯 Objective
Create a neon-style Tetris game with smooth 60FPS animation, particle effects, milestone notifications, sound system, and leaderboard storage.

---

## 🖥️ Tech Requirements
- Use **HTML, CSS, Vanilla JavaScript**
- Use `<canvas>` for rendering
- Single HTML file (no build tools)
- Optimize for **60 FPS performance**

---

## 🧱 Game Board Layout
- Grid: **10 x 20**
- Game container:
  - Width = **1/3 of browser width**
  - Centered both horizontally & vertically
- Fully responsive scaling

---

## 🎮 Core Gameplay
- 7 Tetrominoes (I, O, T, S, Z, J, L)
- Movement:
  - Left / Right / Rotate / Soft drop / Hard drop
- Collision detection
- Line clearing with gravity

---

## 🧮 Scoring
- 1 line = 100  
- 2 lines = 300  
- 3 lines = 500  
- 4 lines = 800  

---

## 🔔 Score Milestone System
- Trigger notification at:
  - 1000, 3000, 5000, 7000...
- Effects:
  - Neon glowing text popup
  - Fade out animation (1–2s)
  - Special sound

---

## 🎨 Visual Style (Neon Cyberpunk)
- Background: black (#000)
- Blocks: neon glow colors
- Use glow effects:
  - Canvas shadowBlur OR CSS effects
- UI text also glowing

---

## ✨ Particle Effects (NEW - IMPORTANT)
- When clearing lines:
  - Generate particle explosion from cleared row
- Particle behavior:
  - Small glowing squares or sparks
  - Random spread direction
  - Fade out over time
- Performance:
  - Use lightweight particle system
  - Limit particle count to avoid lag

---

## 🎞️ Animation System (NEW - IMPORTANT)
- Target: **60 FPS smooth rendering**
- Use `requestAnimationFrame` (NOT setInterval)
- Apply easing for:
  - Line clear animation
  - Piece landing impact (slight bounce or flash)
- Optional:
  - Screen shake effect on hard drop

---

## 🔊 Sound System
Add sounds for:
- Move
- Rotate
- Line clear
- Hard drop
- Game over
- Milestone

Requirements:
- Prevent sound overlap spam
- Add **mute/unmute toggle**

---

## 🏆 Leaderboard System (NEW - IMPORTANT)
- Store high scores using **localStorage**
- Keep top 5 or top 10 scores
- Display leaderboard on screen:
  - Player score list (no login required)
- Update leaderboard when game ends
- Optional:
  - Highlight new high score

---

## 🎮 Controls
- ← → Move  
- ↑ Rotate  
- ↓ Soft drop  
- Space Hard drop  

---

## 🧩 UI Elements
- Score
- Next piece preview
- Start / Restart button
- Leaderboard panel
- Optional:
  - Pause / Resume
  - Hold piece

---

## 💀 Game Over
- Trigger when blocks reach top
- Show overlay:
  - Final score
  - Restart button
  - Leaderboard update

---

## ⚙️ Code Architecture
- Modular structure:
  - Game logic
  - Renderer
  - Input handler
  - Particle system
  - Sound manager
  - Storage (leaderboard)
- Clean, commented code

---

## 📦 Output
- Single HTML file
- Inline CSS + JS
- Ready to run immediately

---

## 🚀 Goal
Deliver a high-quality, visually impressive Tetris game with:
- Smooth animation (60FPS)
- Neon aesthetic
- Particle effects
- Sound system
- Persistent leaderboard

```
