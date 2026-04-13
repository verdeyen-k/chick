# Chick

A two-player browser-based board game. Capture your opponent's chick to win.

## Play

Open `index.html` in a browser, or visit the deployed version. One player creates a game and shares the 4-letter code; the other player joins with that code.

## Rules

### Objective
Capture the enemy's **chick**. If a player has no legal moves, the game is a **draw**.

### Pieces

| Piece | Movement |
|-------|----------|
| **Chick** | 1 square — up, down, left, or right |
| **Hen** | 1 square in any direction (like a chess king) |
| **Rooster** | Jumps exactly 2 squares orthogonally — leaps over any piece in between |

### Starting Setup
Each side starts with:
- **Back row:** hens across the row, with the chick in column 5 and roosters in columns 3 & 6
- **Second row:** all hens

The board flips 180° for the black player so each side always views from their own perspective.

## Tech

- Single-file HTML/CSS/JS — no build step
- [Firebase Realtime Database](https://firebase.google.com/products/realtime-database) for real-time multiplayer sync
- 4-character room codes for matchmaking
- Mobile-first layout (works on phones)
