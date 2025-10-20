# 🐍 Classic Snake Evolution

A fun, fast-paced, and competitive Snake game that revives the nostalgic charm of the original while adding modern features like swipe controls, online leaderboards, and offline play.

## 🕹️ Core Gameplay
- **Goal:** Control the snake to eat food, grow longer, and avoid hitting walls or itself.
- **Movement:** Controlled using swipe gestures —  
  - Swipe Up → Move Up  
  - Swipe Down → Move Down  
  - Swipe Left → Move Left  
  - Swipe Right → Move Right
- **Mechanics:**
  - Each time the snake eats food, its speed increases slightly.
  - The game ends if the snake collides with the wall or its own body.
  - Controls work smoothly in both vertical and horizontal directions using drag/swipe detection for precise, responsive play.


## ⚡ Key Features

### 1. 🏆 Online Leaderboard
- Players can submit their highest scores to a global or regional leaderboard.
- Compare rankings with friends or players worldwide.

### 2. 👤 User Accounts
- You will need to create an account for gameplay and score submissions
- Logged-in users can save and sync scores online.

### 3. 📶 Offline Mode
- Fully playable offline with local score saving once you have successfully signed in
- When reconnected, top scores sync automatically to the leaderboard.

## 🧩 Technical Outline

| Component | Description |
|------------|--------------|
| **Frontend** | Flutter (using Flame Engine for 2D game rendering) |
| **Controls** | Swipe gesture detection (vertical + horizontal) |
| **Backend** | Firebase (Auth + Firestore for leaderboard) |
| **Offline Storage** | Hive or SQLite |
| **Design Style** | Retro pixel art with modern neon glow effects |
| **Sound** | 8-bit chiptune background music that speeds up with gameplay |


## 🖌️ Theme & Design
- **Primary Colors:** Neon green, black, or purple for a retro vibe.
- **Snake Design:** Smooth, segmented, glowing body animation.
- **Backgrounds:** Grid or dynamic neon lines that react to movement.
- **Audio:** Classic arcade sound effects for food collection and collisions.


## 🚀 Next Steps

### 1. 🎯 Level & Speed System 
- Every food item increases the snake’s speed slightly.
- As levels progress, new backgrounds, color themes, or grid sizes appear.
- Increasing difficulty keeps gameplay exciting and challenging.

### 2. 🔥 Rewards & Progress
- Earn points, achievements, or badges based on performance.
- Unlock snake skins, themes, or music tracks after reaching milestones.
- Option to share top scores on social media.

