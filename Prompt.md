```markdown
# 🎮 Prompt: Build a Complete Tetris Game (Web-Based)

## 🧠 Role
You are a senior game developer and frontend engineer. Your task is to build a fully functional, polished Tetris game that runs in the browser.

---

## 🎯 Objective
Create a classic Tetris game with smooth gameplay, responsive controls, score tracking, and increasing difficulty over time.

---

## 🖥️ Tech Requirements
- Use **HTML, CSS, and JavaScript (Vanilla JS preferred)**
- No heavy frameworks (React/Vue optional but not required)
- Must run directly in browser without build tools
- Use `<canvas>` for rendering the game

---

## 🎮 Core Gameplay Features
1. Implement all **7 standard Tetris pieces (Tetrominoes)**:
   - I, O, T, S, Z, J, L

2. Game mechanics:
   - Pieces fall automatically over time
   - Player can:
     - Move left/right
     - Rotate (clockwise at minimum)
     - Soft drop (faster fall)
     - Hard drop (instant drop)
   - Collision detection with:
     - Walls
     - Floor
     - Other pieces

3. Line clearing:
   - Detect full rows
   - Remove them and shift above blocks downward
   - Add score based on number of lines cleared

---

## 🧮 Scoring System
- 1 line = 100 points  
- 2 lines = 300 points  
- 3 lines = 500 points  
- 4 lines (Tetris) = 800 points  

---

## ⏱️ Difficulty Scaling
- Increase falling speed over time or based on score
- Optional: implement levels

---

## 🎨 UI / UX
- Display:
  - Game board (10x20 grid)
  - Score
  - Level (optional)
  - Next piece preview
- Clean, modern UI with minimal styling
- Center the game on screen
- Add start/restart button

---

## 🎮 Controls
- Arrow Left → Move left  
- Arrow Right → Move right  
- Arrow Down → Soft drop  
- Arrow Up → Rotate  
- Spacebar → Hard drop  

---

## 🧩 Additional Features (Optional but preferred)
- Hold piece system
- Ghost piece (preview landing position)
- Pause / Resume
- Game Over screen with restart option

---

## ⚙️ Code Quality
- Write clean, modular code
- Separate logic:
  - Game state
  - Rendering
  - Input handling
- Use comments to explain key logic
- Avoid global clutter

---

## 📦 Output Format
- Provide full working code in a single HTML file
- Include inline CSS and JS (or clearly separated sections)
- Code must run immediately when opened

---

## 🚀 Goal
Deliver a smooth, playable, and visually clear Tetris clone that behaves like the classic game and is easy to extend.

```
