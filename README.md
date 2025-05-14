# Snake-Game-web-app
Snake Game built with HTML5, CSS, and Vanilla JavaScript. The game runs directly in the browser without any external libraries. It features a simple UI, responsive controls (keyboard and on-screen buttons), and high-score saving using browser local Storage.


# Features:
🐍 Classic Snake Gameplay (grow longer, avoid collisions)

🎮 Keyboard Arrow Controls & Touch-Friendly On-Screen Buttons

🏆 High Score Saved Locally (localStorage)

📈 Increasing Difficulty with Level Progression

🎨 Simple Responsive UI with CSS

📲 Mobile & Desktop Friendly

# How It Works:

# Game Board Setup:

The game is drawn on an HTML5 <canvas> element.

Grid size is defined (20x20 tiles), with dynamic food placement and snake rendering.

# Snake Movement:

Snake direction changes based on arrow key inputs or on-screen button clicks.

The snake continuously moves in the set direction at intervals controlled by a speed variable.

# Food Mechanics:

Food appears randomly on the grid.

When the snake eats the food, its length increases, and score increments.

**Scoring & Levels:**

Score increases by 1 with each food eaten.

Every 5 points, the level increases, and game speed becomes faster (speed cap applied).

Game Over Conditions:

The game ends if the snake hits the walls or collides with itself.

Upon game over, the player’s score is compared with the stored high score in localStorage.

If the player beats the high score, it updates and displays the new high score.

Responsive Controls:

Keyboard arrow keys for desktop users.

On-screen directional buttons for mobile users (visible after starting the game).

UI Components:

Score, Level, and High Score display.

Start button toggles game visibility.

Simple, dark-themed UI for focus on gameplay.

Technologies Used:
HTML5 Canvas

JavaScript

CSS3 for styling and layout

LocalStorage API for saving high score

Usage:
Clone or download the repository and open index.html in your browser to play.
