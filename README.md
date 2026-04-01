🐍Snake-Game
## Technical Details

### Technologies Used
-   HTML5 - Structure and Canvas API
-   CSS3  - Styling with gradients and animations
-   JavaScript (Vanilla) - Game logic and rendering

### Key Functions
- `gameLoop()` - Main game loop handling updates and rendering
- `update()` - Updates snake position and checks collisions
- `draw()` - Renders snake, food, and game board
- `handleKeyPress()` - Processes player input
- `generateFood()` - Spawns new food at random location

### Performance
- Optimized canvas rendering
- Efficient collision detection
- Smooth 60 FPS gameplay (adjustable via game speed)
- Local storage for high scores (no server needed)

## Tips & Tricks

🎯 Beginner Tips:
- Start slow and get comfortable with controls
- Plan ahead - don't make sudden direction changes
- Use walls strategically to trap yourself less

🏆 Advanced Strategies:
- Create patterns like spirals to maximize space
- Practice level transitions where speed increases
- Challenge yourself to reach level 10!

## Customization

You can customize the game by editing the HTML file:

```javascript
// Change grid size (in pixels)
const gridSize = 20;

// Adjust starting speed (milliseconds)
let gameSpeed = 100;

// Modify initial snake position
let snake = [{x: Math.floor(tileCount / 2), y: Math.floor(tileCount / 2)}];

// Change canvas dimensions
<canvas id="gameCanvas" width="400" height="400"></canvas>to
