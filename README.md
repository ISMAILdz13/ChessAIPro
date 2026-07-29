<div align="center">

<!-- Animated Chess Banner SVG -->
<svg xmlns="http://www.w3.org/2000/svg" width="600" height="140" viewBox="0 0 600 140">
  <defs>
    <linearGradient id="chessGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#7F00FF;stop-opacity:1">
        <animate attributeName="offset" values="0;0.5;0" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#E100FF;stop-opacity:1">
        <animate attributeName="offset" values="1;0.5;1" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="chessGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="600" height="140" rx="20" fill="url(#chessGrad)"/>
  <!-- Chess pieces -->
  <text x="120" y="70" font-size="42" text-anchor="middle">♞</text>
  <text x="300" y="65" font-family="monospace" font-size="26" font-weight="bold" fill="white" text-anchor="middle" filter="url(#chessGlow)">CHESS AI PRO</text>
  <text x="300" y="95" font-family="monospace" font-size="13" fill="white" text-anchor="middle" opacity="0.9">Minimax Engine | Glassmorphism UI | Vanilla JS</text>
  <text x="480" y="70" font-size="42" text-anchor="middle">♜</text>
  <!-- Animated pieces -->
  <circle cx="80" cy="100" r="5" fill="white" opacity="0.4">
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="520" cy="100" r="4" fill="white" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="1.5s" repeatCount="indefinite"/>
  </circle>
</svg>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
<img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License"/>
<img src="https://img.shields.io/badge/No%20Dependencies-zero-green?style=for-the-badge" alt="No Dependencies"/>

<!-- Animated Status Badge -->
<svg xmlns="http://www.w3.org/2000/svg" width="160" height="28" viewBox="0 0 160 28">
  <rect width="160" height="28" rx="14" fill="#2D2D2D" stroke="#7F00FF" stroke-width="1.5">
    <animate attributeName="stroke" values="#7F00FF;#E100FF;#7F00FF" dur="3s" repeatCount="indefinite"/>
  </rect>
  <circle cx="14" cy="14" r="5" fill="#E100FF">
    <animate attributeName="r" values="5;7;5" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="30" y="18" font-family="monospace" font-size="10" fill="#E100FF" font-weight="bold">GAME READY</text>
</svg>

</div>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| ♟️ **Full Chess Engine** | Complete rules — castling, en passant, pawn promotion |
| 🤖 **AI Opponent** | Minimax algorithm with 5 difficulty levels |
| 🎨 **Glassmorphism UI** | Modern liquid-glass aesthetic with gradient accents |
| 📱 **Responsive** | Works on desktop, tablet, and mobile |
| ↩️ **Undo** | Take back moves (single or dual) |
| 📊 **Evaluation Bar** | Real-time position strength display |
| 🔊 **Sound Effects** | Audio feedback for moves, captures, checks |
| 💾 **Auto-Save** | Game persists in browser localStorage |
| 🔄 **Board Flip** | Rotate 180° for different perspectives |
| ♿ **Accessible** | ARIA labels and keyboard navigation |

---

## 🎯 Difficulty Levels

| Level | Search Depth | Speed |
|-------|-------------|-------|
| Beginner | 2 | Instant |
| Intermediate (default) | 3 | Fast |
| Advanced | 4 | ~1s |
| Master | 4+ | ~2-3s |
| Grandmaster | 5 | Slow (~5-10s) |

---

## 🚀 Quick Start

### Requirements
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- **No dependencies required** — pure vanilla JS/HTML/CSS

### Run
```bash
# Clone
git clone https://github.com/ISMAILdz13/chess-ai-pro.git
cd chess-ai-pro

# Just open index.html in your browser
# Or use a local server:
python3 -m http.server 8000
# Then visit http://localhost:8000
```

---

## 🎮 Controls

| Control | Action |
|---------|--------|
| Click piece | Select |
| Click highlighted square | Move |
| New Game | Reset to start position |
| 🤖 AI Toggle | Enable/disable AI |
| ↩️ Undo | Undo last move(s) |
| 🔄 Flip | Rotate board 180° |

---

## 📁 Project Structure
```
chess-ai-pro/
├── index.html    # Single-file app (HTML + CSS + JS)
├── README.md
└── LICENSE
```

---

## 🔧 How the AI Works

The AI uses the **minimax algorithm** with alpha-beta pruning:

1. **Generate all legal moves** for the current position
2. **Search ahead** to the configured depth (2-5 moves)
3. **Evaluate** each leaf position (material + positional heuristics)
4. **Backpropagate** scores through the tree
5. **Select** the move with the best minimax value

---

## 📜 License

MIT License — see [LICENSE](LICENSE) file.

---

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="400" height="40" viewBox="0 0 400 40">
  <rect x="50" y="18" width="300" height="2" rx="1" fill="#7F00FF" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0.6;0.3" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="200" y="33" font-family="monospace" font-size="10" fill="#666" text-anchor="middle">Made with vanilla JS | No frameworks | No dependencies</text>
</svg>

⭐ **Star this repo if you like it!** ⭐

</div>
