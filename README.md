# 🐍 ULLOSD

> *A retro arcade-style snake game with CRT aesthetics*

![Game Preview](preview.png)

## 🎮 Play Now

**[Click here to play](https://themindexpansionnetwork.github.io/ullosd/)**

Or open `index.html` in any modern browser.

## ✨ Features

- 🕹️ **Classic Snake Gameplay** - Eat food, grow longer, avoid walls and yourself
- 📺 **CRT Monitor Effect** - Authentic retro scanlines and screen curvature
- 🎨 **Neon Glow Aesthetics** - Arcade cabinet styling with glowing elements
- 💥 **Particle Effects** - Explosions when eating food
- 🏆 **High Score Tracking** - Persists between sessions
- ⏸️ **Pause Function** - Spacebar to pause anytime
- 📱 **Responsive Design** - Works on desktop and mobile

## 🎯 Controls

| Key | Action |
|-----|--------|
| `↑` `↓` `←` `→` | Move the snake |
| `Space` | Pause/Resume |
| `Enter` | Start Game |

## 🛠️ Tech Stack

- Pure HTML5 Canvas
- Vanilla JavaScript
- CSS3 with custom animations
- Google Fonts (Press Start 2P)

## 🚀 Local Development

```bash
# Clone the repo
git clone https://github.com/TheMindExpansionNetwork/ullosd.git
cd ullosd

# Open in browser
open index.html
```

Or serve locally:
```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## 🎨 Customization

Edit these values in `index.html`:

```javascript
const gridSize = 20;        // Size of each grid cell
const canvas.width = 400;   // Game width
const canvas.height = 400;  // Game height
```

Change colors in the CSS section to match your style!

## 📜 License

MIT - Built with 💚 by The Mind Expansion Network

---

*"ULLOSD" — Because every snake needs a mysterious retro name*
