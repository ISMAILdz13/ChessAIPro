# ♟️ Chess Pro - AI Chess Game

A beautiful, interactive chess game with AI opponent built with vanilla HTML, CSS, and JavaScript. Features a modern glassmorphism UI, real-time AI engine, and smooth animations.

## 🎮 Features

### Core Gameplay
- **Full Chess Implementation** - Complete chess rules including castling, en passant, and pawn promotion
- **AI Opponent** - Intelligent minimax algorithm with configurable difficulty levels
- **Move Highlighting** - Visual feedback showing selected pieces and available moves
- **Move History** - Click-through game history to review past moves
- **Undo Functionality** - Undo moves (single or dual moves depending on AI mode)

### UI/UX Features
- **Modern Design** - Liquid glass morphism aesthetic with gradient accents
- **Responsive Layout** - Works on desktop and mobile devices
- **Board Flip** - Rotate the board 180° for different perspectives
- **Material Count** - Track captured pieces and material advantage
- **Evaluation Bar** - Real-time position evaluation display
- **Audio Feedback** - Sound effects for moves, captures, and checks
- **Accessibility** - ARIA labels and keyboard navigation support

### Game Settings
- **Difficulty Levels**
  - Beginner (Depth 2)
  - Intermediate (Depth 3) - Default
  - Advanced (Depth 4)
  - Master (Depth 4+)
  - Grandmaster (Depth 5 - Slow)
- **AI Toggle** - Play as white/black or disable AI for two-player mode
- **Game Persistence** - Auto-saves game to browser localStorage

## 🚀 Quick Start

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No external dependencies required

### Usage
1. Open `index.html` in your web browser
2. Click on a piece to select it
3. Click on a highlighted square to move
4. The AI will automatically respond (if enabled)

## 🎯 Game Controls

| Control | Action |
|---------|--------|
| Click Square | Select piece / Make move |
| New Game | Reset to starting position |
| 🤖 AI Toggle | Enable/Disable AI opponent |
| ↩️ Undo | Undo last move(s) |
| 🔄 Flip | Rotate board 180° |
| Difficulty | Change AI search depth |

## 🧠 AI Engine

### Algorithm
- **Minimax with Alpha-Beta Pruning** - Efficient game tree search
- **Piece-Square Tables** - Evaluates piece positioning
- **Material Evaluation** - Assigns values to pieces (♟=1, ♞=3, ♗=3, ♖=5, ♕=9)

### Configuration
```javascript
weights: {
  p: 100,   // Pawn
  n: 320,   // Knight
  b: 330,   // Bishop
  r: 500,   // Rook
  q: 900,   // Queen
  k: 20000  // King
}
```

## 🎨 Design Highlights

### Color Scheme
- **Primary Gradient** - Cyan to Blue (#00d2ff → #3a7bd5)
- **Board Squares** - Light (#94a3b8) and Dark (#334155)
- **Accent Color** - Cyan (#00e5ff)
- **Background** - Deep space gradient with radial blurs

### Visual Effects
- **Glassmorphism** - 12px backdrop blur with transparency
- **Smooth Animations** - 350ms cubic-bezier transitions
- **Piece Movement** - Fluid positioning updates
- **Drop Shadows** - Depth and layering effects

## 💾 Storage

Game data is automatically saved to browser localStorage:
```json
{
  "pgn": "1.e4 e5 2.Nf3...",
  "aiEnabled": true,
  "isFlipped": false,
  "difficulty": "2"
}
```

## 🔊 Audio System

Three sound effects powered by Web Audio API:
- **Move** - 400Hz sine wave (100ms)
- **Capture** - 200Hz square wave (100ms)
- **Check** - 600Hz to 800Hz sweep (200ms)

## 📱 Responsive Design

The game adapts to different screen sizes:
- **Desktop** - Side-by-side layout (board + info panel)
- **Tablet/Mobile** - Stacked vertical layout
- **Minimum** - 320px width support

## 🔧 Technical Details

### Technologies
- **Chess Logic** - Chess.js library (bundled and minified)
- **Graphics** - SVG piece graphics with drop shadows
- **Performance** - Web Workers for AI computation
- **Styling** - Pure CSS with CSS variables for theming

### Browser Compatibility
- ✅ Chrome/Chromium (v80+)
- ✅ Firefox (v74+)
- ✅ Safari (v13+)
- ✅ Edge (v80+)

## 📋 File Structure

```
Chess/
├── index.html          # Main game file (HTML + CSS + JS)
└── README.md          # Documentation
```

## 🎓 How to Customize

### Change Colors
Edit CSS variables in the `<style>` section:
```css
:root {
  --accent-color: #00e5ff;  /* Change accent color */
  --board-light: #94a3b8;   /* Light squares */
  --board-dark: #334155;    /* Dark squares */
}
```

### Adjust AI Difficulty
Modify depth mappings in `CHESS_CONFIG`:
```javascript
depths: { 1: 2, 2: 3, 3: 4, 4: 4, 5: 5 }
```

### Change Animation Speed
```javascript
animationSpeed: 350  // milliseconds
```

## ⚙️ Browser APIs Used

- **Web Audio API** - Sound effects
- **Web Workers** - Background AI computation
- **localStorage** - Game persistence
- **CSS Grid & Flexbox** - Layout
- **CSS Backdrop Filter** - Glassmorphism effect

## 📝 License

Open source - Feel free to use, modify, and distribute.

## 🐛 Known Limitations

- AI search depth is limited by browser performance
- Grandmaster difficulty may cause noticeable delay (2-5 seconds)
- Some older browsers may not support all CSS features

## 🎯 Future Improvements

Potential enhancements:
- [ ] Online multiplayer support
- [ ] Move validation with standard notation input
- [ ] Endgame tablebases
- [ ] Opening book integration
- [ ] Chess engine integration (Stockfish)
- [ ] Game export (PGN/FEN)
- [ ] Dark mode toggle
- [ ] Mobile app version

## 📧 Support

For issues or suggestions, please create an issue in the repository.

---

**Enjoy the game! ♟️**
