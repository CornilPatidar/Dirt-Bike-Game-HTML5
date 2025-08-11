Dirt Bike Game (HTML5)

A small browser game where you ride a dirt bike across simple terrain. Built with HTML5 Canvas and vanilla JavaScript as a weekend learning project.

How to Play
- Arrow keys or WASD to move and balance
  - Left/Right (A/D): accelerate/brake
  - Up/Down (W/S): lean forward/back
- R to restart if you crash

Run Locally
- Double‑click `index.html` to open it in your browser, or
- Use a simple static server (e.g., VS Code “Live Server”).

What I Built
- A basic side‑scrolling bike demo with:
  - Simple physics: gravity, velocity, rotation, friction
  - Keyboard input and a fixed game loop
  - Canvas rendering for the bike sprite, ground, and UI
  - Basic collision and crash/restart

How I Built It
- HTML5 Canvas for drawing the scene each frame
- Vanilla JS `requestAnimationFrame` loop for ~60 FPS updates
- Small physics model using position, velocity, angular rotation
- Simple terrain and camera follow logic

Project Structure
- `index.html`: all game markup, styles, and JavaScript
- `moto.png`, `logo.png`, `pic.jpg`, `pic.png`, `1996.jpg`: art and background assets

What I Learned
- Structuring a basic game loop with delta time
- Handling keyboard input cleanly and preventing default scroll
- Applying lightweight physics and collision checks on Canvas
- Asset loading and drawing performance tips

Help I Got (Resources)
- MDN Web Docs for Canvas API and `requestAnimationFrame`
  - [Canvas API on MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
  - [`requestAnimationFrame` on MDN](https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame)
- Stack Overflow threads for keydown/keyup handling and preventing arrow‑key scrolling
- YouTube tutorials for canvas game patterns (game loop, camera follow)
  - Search terms I used: “html5 canvas game loop”, “canvas platformer physics”
- OpenGameArt.org and Photopea for quick sprite/background tweaks

Roadmap (If I Keep Going)
- Mobile touch controls and on‑screen buttons
- Better terrain generation and checkpoints
- Sound effects and simple music toggle
- Score, timer, and level progression

Notes
- This is intentionally simple and focused on learning. Code is kept minimal and in one file for clarity.


