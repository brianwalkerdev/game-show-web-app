# Wheel of Success

An interactive browser-based word guessing game where players reveal hidden phrases by guessing letters. Built with vanilla JavaScript, HTML5, and CSS3.

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://brianwalkerdev.github.io/game-show-web-app)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

![Wheel of Success - Project Thumbnail](https://github.com/user-attachments/assets/c6600268-1701-446e-8f3c-50968a0447ac)

## 🎮 Live Demo

**[Play the Game →](https://brianwalkerdev.github.io/game-show-web-app)**

## ✨ Features

- **Random Phrase Selection** - Each game features a different hidden phrase
- **Interactive On-Screen Keyboard** - Click letters or use your keyboard
- **Visual Feedback** - Instant visual response for correct and incorrect guesses
- **Lives System** - 5 chances to guess the phrase
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Game Reset** - Play again without refreshing the page
- **Accessibility** - ARIA labels and keyboard navigation support

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, flexbox, transitions
- **JavaScript (ES6)** - DOM manipulation, event handling, game logic
- **No frameworks** - Pure vanilla JavaScript

## 📸 Screenshots

![Game Start Screen](https://github.com/user-attachments/assets/785c4278-2fdb-4bd4-9dfb-60c0d4525eb4)

![Game In Progress](https://github.com/user-attachments/assets/cec6be58-a39c-4b80-9d6e-56f9f2058c4c)

## 🚀 Installation & Usage

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/brianwalkerdev/game-show-web-app.git
   cd game-show-web-app
   ```

2. **Open in browser**
   ```bash
   # Option 1: Open index.html directly in your browser
   open index.html

   # Option 2: Use a local server (recommended)
   npm start
   ```

3. **Start playing!**
   - Click letters to guess
   - Or use your keyboard to type letters
   - Try to reveal the phrase before running out of lives

## 📦 Deployment

### Build for Production

Generate static files ready for deployment:

```bash
npm run build
```

This creates a `dist/` folder with all production-ready files.

### Deploy to Popular Platforms

#### GitHub Pages
```bash
# Push to gh-pages branch
git subtree push --prefix dist origin gh-pages
```

#### Netlify
1. Drag and drop the `dist/` folder to [Netlify](https://app.netlify.com/drop)
2. Or connect your GitHub repo for automatic deployments

#### Vercel
```bash
vercel --prod
```

The app is a static site with no build dependencies, making deployment simple on any hosting platform.

## 🎯 Learning Outcomes

This project demonstrates:
- DOM manipulation and traversal
- Event-driven programming
- Game state management
- Dynamic UI updates
- Responsive CSS design
- Accessibility best practices

## 📁 Project Structure

```
game-show-web-app/
├── index.html          # Main HTML file
├── css/
│   ├── styles.css      # Custom styles
│   └── normalize.css   # CSS reset
├── js/
│   └── main.js         # Game logic
├── images/
│   ├── liveHeart.png   # Lives indicator (active)
│   └── lostHeart.png   # Lives indicator (lost)
├── scripts/
│   └── build.js        # Build script for deployment
├── package.json        # Project metadata
├── LICENSE             # MIT License
└── README.md           # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Brian Walker**

- Website: [brianwalker.dev](https://brianwalker.dev)
- Twitter: [@brianwalkerdev](https://twitter.com/brianwalkerdev)
- GitHub: [@brianwalkerdev](https://github.com/brianwalkerdev)

## 🙏 Acknowledgments

- Inspired by classic word guessing games
- Built as part of a JavaScript learning path
- Designed with accessibility and user experience in mind

---

⭐ Star this repo if you found it helpful!
