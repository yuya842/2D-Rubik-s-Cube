# 2D Rubik's Cube (3²) with Auto & God Solvers
A novel 2D Rubik's Cube puzzle (3x3 grid, 4-axis rotation) playable right in your browser, featuring both a history replayer and an AI-powered shortest-path solver!

## 🧩 Key Features
- **Mind-Bending 2D Logic**: Inside a 3x3 grid, four 2x2 rotation areas overlap. Turning an area changes not only the positions of the tiles but also the orientations of their colored borders!
- **The Core Center Piece**: The exact center tile is shared by all 4 rotation axes, making it the most volatile and tricky piece to control.
- **Dual Solver Modes**:
  - **History Replay Solve**: Instantly trace your steps backward to see exactly how you messed up.
  - **⚡ God's Solve (Shortest Path)**: Powered by a built-in BFS algorithm. No matter how scrambled it is, the AI calculates the ultimate shortest path to solution in milliseconds!

---

## 📋 Move Notation
This project uses the following official notation for movement:

| Code | Area | Direction |
| :--- | :--- | :--- |
| **TL** | Top-Left | Clockwise (90°) |
| **TL'** | Top-Left | Counter-Clockwise (90°) |
| **TL2** | Top-Left | Half-Turn (180°) |
| **TR** | Top-Right | Clockwise (90°) |
| **TR'** | Top-Right | Counter-Clockwise (90°) |
| **TR2** | Top-Right | Half-Turn (180°) |
| **BL** | Bottom-Left | Clockwise (90°) |
| **BL'** | Bottom-Left | Counter-Clockwise (90°) |
| **BL2** | Bottom-Left | Half-Turn (180°) |
| **BR** | Bottom-Right | Clockwise (90°) |
| **BR'** | Bottom-Right | Counter-Clockwise (90°) |
| **BR2** | Bottom-Right | Half-Turn (180°) |

---

## 🚀 How to Play
1. Open `index.html` in any modern web browser.
2. Click **"Shuffle"** to randomly scramble the board.
3. Use the on-screen arrow buttons (`↻` / `↺`) or type your own custom algorithms in the **EXECUTE NOTATION** box to solve it!
4. If you get stuck, let the **⚡ God's Solve** show you the ultimate optimal way back to the solved state.

## 🛠️ Roadmap
- [x] Real-time display of operation history (Move Notation) on screen
- [x] Execute custom notation sequences (e.g., `TL TR' BL2`) via text input
- [x] Integrate a built-in BFS AI solver to find and execute the "God's Number" shortest path
