# 🐍 Snake Game

A classic Snake Game built with pure HTML5, CSS3, and JavaScript. Control the snake to eat food, grow longer, and achieve the highest score possible without hitting the walls or yourself!

## ✨ Features

- **Score Tracking System**: Real-time score display that updates as you eat food
- **High Score Persistence**: Your best score is saved locally using localStorage and persists across sessions
- **Responsive Design**: Fully playable on both desktop and mobile devices
- **Touch Controls**: On-screen arrow buttons for mobile gameplay
- **Keyboard Controls**: Arrow keys support for desktop players
- **Collision Detection**: Game detects wall collisions and self-collisions
- **Smooth Gameplay**: Consistent game loop with 100ms interval for smooth snake movement
- **Auto Replay**: Quick restart functionality after game over
- **Modern UI**: Clean and attractive dark-themed interface with subtle shadows

## 🎮 How to Play

### Controls

**Desktop:**
- **Arrow Up** ⬆️ - Move Up
- **Arrow Down** ⬇️ - Move Down
- **Arrow Left** ⬅️ - Move Left
- **Arrow Right** ➡️ - Move Right

**Mobile:**
- Use the on-screen arrow buttons at the bottom of the game board

### Rules

1. Control the snake to eat the red food blocks
2. Each food eaten increases your score by 1 and makes the snake longer
3. Avoid hitting the walls (game board boundaries)
4. Avoid running into your own body
5. Try to beat your high score!

## 🛠️ Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling, animations, and responsive design
- **JavaScript (ES6)** - Game logic and DOM manipulation
- **LocalStorage API** - High score persistence
- **Font Awesome 6.3.0** - Arrow icons for controls
- **Google Fonts (Open Sans)** - Typography

## 📦 Installation & Usage

### Option 1: Direct File Opening
1. Clone or download this repository
```bash
git clone https://github.com/yourusername/snake-game.git
```
2. Navigate to the project folder
3. Open `index.html` in your web browser

### Option 2: Live Server (Recommended for Development)
1. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: GitHub Pages
1. Fork this repository
2. Go to repository Settings → Pages
3. Select the main branch as source
4. Your game will be live at `https://lequanglong2410.github.io/Snake-Game/`

## 🎯 Game Mechanics

- **Grid Size**: 30x30 cells
- **Initial Snake Position**: (5, 5)
- **Game Speed**: 100ms per frame
- **Food Spawn**: Random position on each consumption
- **Score Increment**: +1 per food eaten

## 📂 Project Structure

```
snake-game/
│
├── index.html          # Main HTML file
├── style.css          # Styling and responsive design
├── index.js           # Game logic and functionality
├── screenshot.jpg     # Game preview image
└── README.md          # Project documentation
```

## 🌟 Future Improvements

- [ ] Add difficulty levels (speed variations)
- [ ] Implement pause/resume functionality
- [ ] Add sound effects and background music
- [ ] Create power-ups and special food items
- [ ] Add obstacles and different game modes
- [ ] Implement leaderboard system

## 👨‍💻 Author

**Le Quang Long**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---

⭐ If you like this project, please give it a star on GitHub!
