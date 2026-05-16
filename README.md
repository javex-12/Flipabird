# 🐦 Flipabird - 3D Flappy Bird Game

A stunning 3D recreation of the classic Flappy Bird game built with **Three.js** and vanilla JavaScript. Navigate through pipes and obstacles in a beautiful three-dimensional environment.

## 🎮 Features

- **3D Graphics:** Immersive Three.js-powered 3D environment
- **Responsive Design:** Seamless gameplay on all devices (desktop, tablet, mobile)
- **Simple Controls:** Press space bar or tap to flap the bird's wings
- **Smooth Animations:** Fluid 3D camera and object movements
- **High Performance:** Optimized rendering for fast, lag-free gameplay
- **Progressive Web App:** Install as an app and play offline

## 🛠️ Tech Stack

- **3D Engine:** Three.js (r128)
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Deployment:** Compatible with all modern browsers and PWA hosts

## 🚀 Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/javex-12/Flipabird.git
   ```

2. Navigate to the project:
   ```bash
   cd Flipabird
   ```

3. Run a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

4. Open your browser and visit `http://localhost:8000`

### Direct Play

Simply open `index.html` in any modern web browser—no installation required!

## 🎮 How to Play

1. **Start the Game:** Click the play button on the home screen
2. **Controls:** 
   - **Desktop:** Press `SPACEBAR` to flap
   - **Mobile:** Tap anywhere on the screen to flap
3. **Objective:** Navigate through the pipes and obstacles
4. **Avoid:** Don't hit the pipes or the ground
5. **Score:** Each successful pipe passage increases your score

## 📦 File Structure

```
├── index.html              # Main HTML file
├── styles/
│   └── style.css           # Game styling and animations
├── js/
│   └── main.js             # Game logic using Three.js
└── README.md               # This file
```

## 🎨 Customization

### Modify Game Difficulty

Edit `js/main.js` to adjust:
- Pipe spacing
- Game speed
- Gravity/flap force
- Camera field of view

### Change 3D Models

Modify the Three.js scene in `js/main.js`:
- Bird geometry and material
- Pipe design
- Background environment
- Lighting setup

## 🌐 Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 PWA Installation

Install on your device's home screen:
1. Open the game in your browser
2. Look for "Install" or "Add to Home Screen" option
3. Enjoy offline gameplay!

## 🔗 Deploy

Deploy to popular platforms:

- **Netlify:** Drag and drop the repository or connect GitHub
- **Vercel:** Push to GitHub and auto-deploy
- **GitHub Pages:** Enable GitHub Pages in repository settings
- **Any Static Host:** Upload files via FTP or file manager

## 🐛 Troubleshooting

**Black screen on load?**
- Ensure your browser supports WebGL
- Try a different modern browser
- Clear browser cache and reload

**Game feels laggy?**
- Check your browser's GPU acceleration is enabled
- Close other memory-intensive applications
- Try reducing your monitor's resolution

**Controls not responding?**
- Click on the game canvas to ensure it has focus
- Check that JavaScript is enabled in your browser

## 🎯 Future Enhancements

- [ ] Sound effects and music
- [ ] Difficulty levels
- [ ] Leaderboard system
- [ ] Multiple bird skins
- [ ] Special power-ups
- [ ] Obstacle variations

## 📄 License

This project is open-source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Share gameplay feedback

## 📧 Contact

For questions or feedback, open an issue on GitHub or reach out to javex-12.

---

**Built with ❤️ using Three.js**

*Created to celebrate the classic Flappy Bird, reimagined in stunning 3D*
