<div align="center">

<!-- Animated Chess Banner -->
<svg xmlns="http://www.w3.org/2000/svg" width="680" height="160" viewBox="0 0 680 160">
  <defs>
    <linearGradient id="chessBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#6366f1;stop-opacity:1">
        <animate attributeName="offset" values="0;0.5;0" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#8b5cf6;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ec4899;stop-opacity:1">
        <animate attributeName="offset" values="1;0.5;1" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="chessGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="680" height="160" rx="25" fill="url(#chessBg)"/>
  <!-- Chess pieces -->
  <text x="80" y="80" font-size="48" text-anchor="middle" fill="white" opacity="0.3">♞</text>
  <text x="600" y="100" font-size="42" text-anchor="middle" fill="white" opacity="0.25">♜</text>
  <text x="340" y="65" font-family="monospace" font-size="28" font-weight="bold" fill="white" text-anchor="middle" filter="url(#chessGlow)">CHESS AI PRO</text>
  <text x="340" y="98" font-family="monospace" font-size="14" fill="white" text-anchor="middle" opacity="0.9">Minimax Engine | Glassmorphism UI | Zero Dependencies</text>
  <!-- Animated particles -->
  <circle cx="60" cy="40" r="6" fill="white" opacity="0.4">
    <animate attributeName="opacity" values="0.4;0.9;0.4" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="r" values="6;10;6" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="620" cy="120" r="5" fill="white" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="160" cy="130" r="4" fill="white" opacity="0.35">
    <animate attributeName="opacity" values="0.35;0.8;0.35" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="520" cy="45" r="5" fill="white" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="5;8;5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <rect x="170" y="120" width="340" height="3" rx="1.5" fill="white" opacity="0.15">
    <animate attributeName="width" values="100;340;100" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="x" values="270;170;270" dur="5s" repeatCount="indefinite"/>
  </rect>
</svg>

<!-- Badges -->
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
<img src="https://img.shields.io/badge/Dependencies-Zero-success?style=for-the-badge" alt="No Dependencies"/>
<img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License"/>
<img src="https://img.shields.io/badge/Single%20File-100%25-blueviolet?style=for-the-badge" alt="Single File"/>
<img src="https://img.shields.io/github/stars/ISMAILdz13/chess-ai-pro?style=for-the-badge" alt="Stars"/>

<!-- Animated Status -->
<svg xmlns="http://www.w3.org/2000/svg" width="170" height="28" viewBox="0 0 170 28">
  <rect width="170" height="28" rx="14" fill="#2D2D2D" stroke="#6366f1" stroke-width="1.5">
    <animate attributeName="stroke" values="#6366f1;#ec4899;#6366f1" dur="3s" repeatCount="indefinite"/>
  </rect>
  <circle cx="14" cy="14" r="5" fill="#6366f1">
    <animate attributeName="r" values="5;7;5" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="30" y="18" font-family="monospace" font-size="10" fill="#6366f1" font-weight="bold">GAME READY</text>
</svg>

</div>

---

## 📋 Table of Contents

| # | Section | # | Section |
|---|---------|---|---------|
| 1 | [Overview](#-overview) | 6 | [AI Engine](#-ai-engine) |
| 2 | [Features](#-features) | 7 | [Architecture](#-architecture) |
| 3 | [Installation](#-installation) | 8 | [Project Structure](#-project-structure) |
| 4 | [Controls](#-controls) | 9 | [FAQ](#-faq) |
| 5 | [Difficulty Levels](#-difficulty-levels) | 10 | [Credits](#-credits) |

---

## ♟️ Overview

**Chess AI Pro** is a beautiful, interactive chess game with an AI opponent — built entirely with **vanilla HTML, CSS, and JavaScript**. No frameworks, no libraries, no build tools. Just open `index.html` and play.

The game features a **minimax algorithm with alpha-beta pruning** for the AI, a modern **glassmorphism UI** with gradient accents, smooth animations, sound effects, and full chess rule implementation including castling, en passant, and pawn promotion.

---

## ✨ Features

### Core Gameplay

| Feature | Description |
|---------|-------------|
| ♟️ **Full Chess Rules** | Castling (kingside + queenside), en passant, pawn promotion |
| 🤖 **AI Opponent** | Minimax with alpha-beta pruning, 5 difficulty levels |
| 🎯 **Move Highlighting** | Visual feedback for selected pieces and legal moves |
| 📜 **Move History** | Click-through game history to review past moves |
| ↩️ **Undo** | Undo moves (single in 2-player, dual moves vs AI) |
| 👑 **Checkmate Detection** | Automatic checkmate, stalemate, and draw detection |
| 🔄 **Board Flip** | Rotate 180° to play from either perspective |
| 📊 **Material Counter** | Track captured pieces and material advantage |
| 📈 **Evaluation Bar** | Real-time position evaluation display |

### UI/UX

| Feature | Description |
|---------|-------------|
| 🎨 **Glassmorphism** | Liquid-glass aesthetic with gradient accents |
| 📱 **Responsive** | Works on desktop, tablet, and mobile |
| 🔊 **Sound Effects** | Audio feedback for moves, captures, and checks |
| ♿ **Accessibility** | ARIA labels, keyboard navigation, screen reader support |
| 💾 **Auto-Save** | Game persists in browser localStorage |

---

## 📦 Installation

<details open>
<summary><b>Quick Start (No Dependencies)</b></summary>

<br>

```bash
# Clone the repo
git clone https://github.com/ISMAILdz13/chess-ai-pro.git
cd chess-ai-pro

# Option 1: Just open index.html in your browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows

# Option 2: Use a local server (recommended)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

</details>

<details>
<summary><b>GitHub Pages Deployment</b></summary>

<br>

```bash
# Push to your repo, then enable GitHub Pages:
# Settings → Pages → Source → Deploy from branch → main
# Your game will be live at:
# https://ISMAILdz13.github.io/chess-ai-pro/
```

</details>

<details>
<summary><b>Embed in Website</b></summary>

<br>

```html
<iframe src="https://ISMAILdz13.github.io/chess-ai-pro/" 
        width="100%" height="800" frameborder="0">
</iframe>
```

</details>

---

## 🎮 Controls

| Control | Action | Keyboard |
|---------|--------|----------|
| Click piece | Select piece | — |
| Click highlighted square | Make move | — |
| New Game | Reset to starting position | `N` |
| 🤖 AI Toggle | Enable/disable AI opponent | `A` |
| ↩️ Undo | Undo last move(s) | `U` |
| 🔄 Flip | Rotate board 180° | `F` |
| Difficulty dropdown | Change AI search depth | `D` |

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `N` | New game |
| `A` | Toggle AI |
| `U` | Undo |
| `F` | Flip board |
| `D` | Focus difficulty selector |
| `Esc` | Deselect piece |

---

## 🎯 Difficulty Levels

<div align="center">

| Level | Search Depth | Thinking Time | Best For |
|-------|-------------|--------------|----------|
| Beginner | 2 | Instant | Learning the basics |
| Intermediate (default) | 3 | < 1s | Casual play |
| Advanced | 4 | ~1-2s | Competitive |
| Master | 4+ | ~2-4s | Strong challenge |
| Grandmaster | 5 | ~5-15s | Maximum difficulty |

<!-- Difficulty visualization SVG -->
<svg xmlns="http://www.w3.org/2000/svg" width="600" height="120" viewBox="0 0 600 120">
  <defs>
    <linearGradient id="diffGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#43e97b"/>
      <stop offset="25%" style="stop-color:#4facfe"/>
      <stop offset="50%" style="stop-color:#f093fb"/>
      <stop offset="75%" style="stop-color:#FF4B2B"/>
      <stop offset="100%" style="stop-color:#f5576c"/>
    </linearGradient>
  </defs>
  <!-- Bar chart -->
  <rect x="20" y="80" width="80" height="20" rx="4" fill="#43e97b" opacity="0.9"/>
  <text x="60" y="75" font-family="monospace" font-size="9" fill="#43e97b" text-anchor="middle">Depth 2</text>

  <rect x="130" y="65" width="80" height="35" rx="4" fill="#4facfe" opacity="0.9"/>
  <text x="170" y="60" font-family="monospace" font-size="9" fill="#4facfe" text-anchor="middle">Depth 3</text>

  <rect x="240" y="50" width="80" height="50" rx="4" fill="#f093fb" opacity="0.9"/>
  <text x="280" y="45" font-family="monospace" font-size="9" fill="#f093fb" text-anchor="middle">Depth 4</text>

  <rect x="350" y="35" width="80" height="65" rx="4" fill="#FF4B2B" opacity="0.9"/>
  <text x="390" y="30" font-family="monospace" font-size="9" fill="#FF4B2B" text-anchor="middle">Depth 4+</text>

  <rect x="460" y="20" width="80" height="80" rx="4" fill="#f5576c" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.6;0.9" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="500" y="15" font-family="monospace" font-size="9" fill="#f5576c" text-anchor="middle">Depth 5</text>

  <text x="300" y="115" font-family="monospace" font-size="8" fill="#666" text-anchor="middle">Thinking Time &amp; Difficulty Scale</text>
</svg>

</div>

---

## 🤖 AI Engine

The AI uses the **minimax algorithm with alpha-beta pruning** — the classic approach for two-player zero-sum games like chess.

### How It Works

<details open>
<summary><b>Algorithm Breakdown</b></summary>

<br>

1. **Move Generation** — All legal moves are generated for the current position using the chess engine library (embedded in `index.html`)
2. **Tree Search** — The algorithm searches ahead to the configured depth (2-5 moves)
3. **Position Evaluation** — Each leaf position is scored using:
   - **Material balance** (piece values: pawn=1, knight=3, bishop=3, rook=5, queen=9)
   - **Piece-square tables** (positional bonuses for piece placement)
   - **Mobility** (number of legal moves available)
   - **King safety** (castling status, pawn shield)
4. **Alpha-Beta Pruning** — Branches that can't affect the final decision are pruned, dramatically reducing the search space
5. **Move Selection** — The move with the best minimax value is chosen

</details>

<details>
<summary><b>Position Evaluation Formula</b></summary>

<br>

```
Score = Σ(material_value[piece] + piece_square_table[piece][square])
        + mobility_bonus
        + king_safety_bonus
        - opponent_threats
```

**Piece Values:**
| Piece | Value |
|-------|-------|
| Pawn | 1 |
| Knight | 3 |
| Bishop | 3 |
| Rook | 5 |
| Queen | 9 |
| King | ∞ (not capturable) |

</details>

---

## 🏗️ Architecture

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="640" height="300" viewBox="0 0 640 300">
  <defs>
    <linearGradient id="archG1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#6366f1"/><stop offset="100%" style="stop-color:#8b5cf6"/>
    </linearGradient>
    <linearGradient id="archG2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#ec4899"/><stop offset="100%" style="stop-color:#f5576c"/>
    </linearGradient>
    <linearGradient id="archG3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#4facfe"/><stop offset="100%" style="stop-color:#00f2fe"/>
    </linearGradient>
    <filter id="archS"><feDropShadow dx="2" dy="3" stdDeviation="3" flood-opacity="0.3"/></filter>
    <marker id="archA" markerWidth="10" markerHeight="7" refX="9" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#666"/>
    </marker>
  </defs>

  <text x="320" y="25" font-family="monospace" font-size="14" font-weight="bold" fill="#333" text-anchor="middle">Chess AI Pro Architecture</text>

  <!-- UI Layer -->
  <rect x="30" y="50" width="160" height="60" rx="12" fill="url(#archG1)" filter="url(#archS)"/>
  <text x="110" y="78" font-family="monospace" font-size="11" fill="white" text-anchor="middle" font-weight="bold">UI Layer</text>
  <text x="110" y="95" font-family="monospace" font-size="8" fill="white" text-anchor="middle">Glassmorphism + CSS</text>

  <!-- Chess Engine -->
  <rect x="240" y="50" width="160" height="60" rx="12" fill="url(#archG2)" filter="url(#archS)"/>
  <text x="320" y="78" font-family="monospace" font-size="11" fill="white" text-anchor="middle" font-weight="bold">Chess Engine</text>
  <text x="320" y="95" font-family="monospace" font-size="8" fill="white" text-anchor="middle">Rules + Validation</text>

  <!-- AI Engine -->
  <rect x="450" y="50" width="160" height="60" rx="12" fill="url(#archG3)" filter="url(#archS)"/>
  <text x="530" y="78" font-family="monospace" font-size="11" fill="white" text-anchor="middle" font-weight="bold">AI Engine</text>
  <text x="530" y="95" font-family="monospace" font-size="8" fill="white" text-anchor="middle">Minimax + Pruning</text>

  <!-- Arrows -->
  <line x1="190" y1="80" x2="235" y2="80" stroke="#666" stroke-width="2" marker-end="url(#archA)"/>
  <line x1="400" y1="80" x2="445" y2="80" stroke="#666" stroke-width="2" marker-end="url(#archA)"/>

  <!-- Evaluation -->
  <rect x="240" y="160" width="160" height="50" rx="12" fill="#2D2D2D" stroke="#ec4899" stroke-width="1.5" filter="url(#archS)">
    <animate attributeName="stroke" values="#ec4899;#6366f1;#ec4899" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="320" y="190" font-family="monospace" font-size="11" fill="#ec4899" text-anchor="middle" font-weight="bold">Evaluation</text>

  <line x1="530" y1="110" x2="380" y2="160" stroke="#666" stroke-width="1.5" marker-end="url(#archA)" stroke-dasharray="4,3"/>

  <!-- Persistence -->
  <rect x="30" y="160" width="160" height="50" rx="12" fill="#2D2D2D" stroke="#4facfe" stroke-width="1.5" filter="url(#archS)"/>
  <text x="110" y="190" font-family="monospace" font-size="11" fill="#4facfe" text-anchor="middle" font-weight="bold">localStorage</text>

  <line x1="110" y1="110" x2="110" y2="155" stroke="#666" stroke-width="1.5" marker-end="url(#archA)"/>

  <!-- Output -->
  <rect x="200" y="250" width="240" height="35" rx="10" fill="#2D2D2D" stroke="#43e97b" stroke-width="1.5">
    <animate attributeName="stroke" values="#43e97b;#4facfe;#43e97b" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="320" y="272" font-family="monospace" font-size="11" fill="#43e97b" text-anchor="middle" font-weight="bold">✓ Best Move Selected</text>

  <line x1="320" y1="210" x2="320" y2="245" stroke="#666" stroke-width="2" marker-end="url(#archA)"/>
</svg>

</div>

### Data Flow
1. **Player clicks** → UI Layer captures input → Chess Engine validates move
2. Chess Engine updates board state → UI re-renders pieces
3. AI Engine generates legal moves → searches game tree → evaluates positions
4. Best move is selected → Chess Engine applies it → UI animates the move
5. Game state saved to localStorage

---

## 📁 Project Structure

```
chess-ai-pro/
├── index.html    # Single-file app — all HTML, CSS, and JS
├── README.md     # This file
├── LICENSE        # MIT License
└── .gitignore
```

> **Everything is in one file.** The chess engine, AI logic, UI, styling, and sound effects are all embedded in `index.html`. No build step, no dependencies, no npm install.

---

## ❓ FAQ

<details>
<summary><b>Do I need to install anything?</b></summary>

No! Just open `index.html` in any modern browser. No dependencies, no build tools, no server required.

</details>

<details>
<summary><b>How strong is the AI?</b></summary>

At Grandmaster level (depth 5), the AI is quite challenging for casual players. It won't beat a titled player, but it provides a solid game for most people. Depth 5 with alpha-beta pruning typically evaluates tens of thousands of positions per move.

</details>

<details>
<summary><b>Can I play against another human?</b></summary>

Yes! Toggle off the AI button (🤖 AI: OFF) and two players can take turns on the same device.

</details>

<details>
<summary><b>Does it work on mobile?</b></summary>

Yes, the UI is fully responsive. Tap to select pieces and tap highlighted squares to move. The layout adapts to phone and tablet screens.

</details>

<details>
<summary><b>Is my game saved?</b></summary>

Yes, the game state is automatically saved to your browser's localStorage. Close the tab and come back later — your game will still be there.

</details>

<details>
<summary><b>Can I embed this on my website?</b></summary>

Yes! Use an iframe pointing to the GitHub Pages URL:
```html
<iframe src="https://ISMAILdz13.github.io/chess-ai-pro/" 
        width="100%" height="800" frameborder="0"></iframe>
```

</details>

<details>
<summary><b>What chess rules are supported?</b></summary>

All standard chess rules: castling (kingside + queenside), en passant, pawn promotion (with piece selection dialog), check, checkmate, stalemate, threefold repetition, insufficient material, and the 50-move rule.

</details>

<details>
<summary><b>How does the evaluation bar work?</b></summary>

The evaluation bar shows the relative position strength. A full bar pointing toward White means White is winning. The score (e.g., +2.5) represents the material advantage in pawns.

</details>

---

## 👤 Credits

- **Developer**: ISMAILdz13 (@ISMAILdz13)
- **Repository**: [github.com/ISMAILdz13/chess-ai-pro](https://github.com/ISMAILdz13/chess-ai-pro)
- **Chess Engine**: Custom implementation embedded in `index.html`
- **AI Algorithm**: Minimax with alpha-beta pruning

---

## 📄 License

MIT License — see [LICENSE](LICENSE) file.

---

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="500" height="50" viewBox="0 0 500 50">
  <defs>
    <linearGradient id="chessFooter" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#6366f1;stop-opacity:0">
        <animate attributeName="offset" values="0;1;0" dur="5s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#ec4899;stop-opacity:0">
        <animate attributeName="offset" values="1;0;1" dur="5s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  <rect x="30" y="20" width="440" height="2" rx="1" fill="url(#chessFooter)"/>
  <text x="250" y="42" font-family="monospace" font-size="10" fill="#666" text-anchor="middle">Pure vanilla JS | No frameworks | No dependencies | Single file | by ISMAILdz13</text>
</svg>

⭐ **Star this repo if you like it!** ⭐

</div>
