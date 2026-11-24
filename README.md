# Elemental Quoridor

A self-contained, turn-based browser game inspired by Quoridor. No dependencies or build step are needed: open `index.html` in a browser and select Player vs Player or Player vs Bot to start a match.

## How to play

- Each team controls Fire, Water, Earth, Air, and Lightning on a 27 × 27 board. The Ember team starts at the bottom and the Tide team at the top.
- Move one piece or place one two-edge wall on your turn. Reach the opposite edge with any piece to win. Each team starts with 22 walls (20 standard, plus Earth's two-wall passive). Walls cannot overlap or block every route to a goal.
- Select a piece to see reachable tiles. Click a wall anchor to place a wall; switch between horizontal and vertical first. Press **End turn** to pass without moving or placing a wall.
- Collect glowing pickups for temporary Quickstep (extra movement), Phase (wall-crossing), or Focus (faster ability cooldowns).
- Each element has its own role, base speed, passive, and cooldown ability:
  - **Fire** — Attack, speed 2; +1 movement each turn; Flame Dash adds 2 steps.
  - **Water** — Support, speed 1; buffs last 1 extra turn; Spring Tide gives the team +1 movement for 2 turns.
  - **Earth** — Tank, speed 1; starts with 2 extra walls; Stonecraft places a free wall.
  - **Air** — Defense, speed 3; +1 movement each turn; Updraft ignores walls for one move.
  - **Lightning** — Attack, speed 2; collects adjacent pickups; Flash Step teleports up to 5 tiles.
- Select an element and use its ability from the sidebar. Press Escape to cancel an ability or wall placement.
- In Player vs Bot, the Elemental Guide moves the Tide team.
