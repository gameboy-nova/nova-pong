## 🎮 Ping

### 📝 Description  
Classic Pong-style game where two players bounce a ball and try to prevent it from passing their paddle.

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
