# Snake Game

A mobile-friendly Snake game built in a single HTML file with a dark space theme and sarcastic developer-themed death messages.

## Features

- **Three difficulty levels** — Easy, Medium, Hard — each with progressive speed acceleration as your score grows
- **Mobile support** — touch swipe gestures on the canvas and an on-screen D-pad for phone/tablet play
- **Keyboard controls** — Arrow keys or WASD to move, Space or P to pause
- **Pause/resume** — pause button in the UI or the D-pad center button
- **Dev roast mode** — snarky death messages on game over ("merged to main without testing. classic.")
- **Particle effects** — burst animation on food pickup
- **Animated background** — flickering star field with a subtle grid overlay
- **Score tracking** — current score and session best score displayed live

## How to Play

Open `snake_dev_roast_mobile.html` in any modern browser — no server or build step needed.

| Input | Action |
|-------|--------|
| Arrow keys / WASD | Change direction |
| Space / P | Pause / Resume |
| Swipe on canvas | Change direction (mobile) |
| D-pad buttons | Change direction (mobile) |
| D-pad center (D) | Pause / Resume |

## Difficulty

| Level | Base speed | Acceleration |
|-------|-----------|--------------|
| Easy  | 165 ms/tick | +8 ms per 5 points |
| Med   | 110 ms/tick | +12 ms per 5 points |
| Hard  | 60 ms/tick  | +18 ms per 5 points |

Speed is capped at a minimum of 40 ms/tick regardless of level.
