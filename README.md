<p align="center">
<img src="https://github.com/user-attachments/assets/f6ac32bd-76f9-4957-8dea-ec592b3a1954" width="300">
</p>

<h1 align="center"> 
Ping
</h1>

<p align="center">
Classic Pong-style game where two players bounce a ball and try to prevent it from passing their paddle.
</p>

---
## 🎮 Gameplay Showcase

Here’s a quick look at the game in action:
<p align="center">
<img src="https://github.com/user-attachments/assets/3df3f836-1959-4a81-a6e0-cc8903b7ac0c" width="500">
</p>

---

### 🕹️ Controls

| Button   | Action        |
|----------|---------------|
| A_UP     | P1 Move up    |
| A_DOWN   | P1 Move down  |
| B_UP     | P2 Move up    |
| B_DOWN   | P2 Move down  |
| EXIT     | Exit game     |

---

### 🧠 Logic Overview  
The ball moves with a velocity vector and bounces off paddles and screen boundaries.  
Players must time paddle movement to reflect the ball.

---

### 🧩 Game Loop Structure  
1. Move paddles  
2. Move ball  
3. Detect collision  
4. Update screen  

---

### ❌ End Conditions  
- One player reaches the score cap  
- Exit input is received  

---

### 🧪 Notes & Improvements  
- Add ball acceleration over time for increased difficulty
