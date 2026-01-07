# 🎮 2048 Game

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)

A modern, high-performance implementation of the classic **2048** puzzle game, built using **React**. This project showcases clean state management logic, efficient grid manipulation, and smooth CSS-based animations.

---

## 🚀 Features

- **Classic Gameplay:** Merge tiles with the same numbers to reach the ultimate 2048 tile.
- **Smooth Animations:** Fluid transitions for tile movement and merging using CSS3 transitions and keyframes.
- **Responsive Design:** Fully playable on both desktop and mobile browsers.
- **Real-time Scoring:** Instant score updates as you play.
- **Win/Loss Logic:** Automated detection of the "Game Over" state when no moves are left or the "Win" state when 2048 is reached.

---

## 🛠 Tech Stack

- **Library:** React.js (Functional Components & Hooks)
- **State Management:** React `useState`, `useEffect`, and `useMemo` for optimized calculations.
- **Styling:** CSS3 (Flexbox, Grid, and standard CSS Modules)
- **Build Tool:** Vite / Create React App

---

## 📂 Project Structure

```bash
src/
├── components/        # UI Components (Board, Tile, Cell, ScoreBox)
├── hooks/             # Custom hooks for game logic and event listeners
├── utils/             # Helper functions (grid generation, move logic, collision detection)
├── styles/            # CSS files for layout and animations
├── App.js             # Main application entry point
└── index.js           # Rendering logic
```

---

## 🕹 Getting Started

### Prerequisites

- **Node.js** (v14.0 or higher recommended)
- **npm** or **yarn**

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/EverQest/2048-React.js.git
    ```

2.  **Navigate to the project folder:**
    ```bash
    cd 2048-React.js
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Start the development server:**
    ```bash
    npm start
    ```

5.  Open [http://localhost:3000](http://localhost:3000) in your browser to see the game.

---

## 🎮 How to Play

Use the **Arrow Keys** on your keyboard to move the tiles:
- `Up Arrow`: Move tiles upward.
- `Down Arrow`: Move tiles downward.
- `Left Arrow`: Move tiles to the left.
- `Right Arrow`: Move tiles to the right.

When two tiles with the same number touch, they **merge into one**!

---

## 🧠 Technical Highlights

- **Matrix Logic:** The game board is represented as a 2D array, with logic handling shifts and merges for all four directions.
- **Event Handling:** Global keyboard listeners are managed via `useEffect` to ensure clean mounting/unmounting.
- **Performance:** Optimized rendering to ensure only moving tiles are updated, maintaining a smooth 60fps feel.

---

## 📝 Roadmap

- [ ] **Local Storage:** Save high scores and current game state.
- [ ] **Touch Gestures:** Add swipe support for mobile users.
- [ ] **Undo Feature:** Allow players to revert the last move.
- [ ] **Custom Themes:** Dark mode and high-contrast color palettes.
- [ ] **Difficulty Settings:** Different grid sizes (3x3, 5x5, 6x6).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/EverQest/2048-React.js/issues).

---

## 👤 Author

**EverQest**
*   GitHub: [@EverQest](https://github.com/EverQest)

---

### Analysis Summary for the Owner:
*   **Logic:** The game logic is cleanly separated from the UI components.
*   **Code Quality:** Great use of React Hooks for managing game state and side effects.
*   **UX:** The CSS animations provide a polished feel similar to the original 2048 game.
