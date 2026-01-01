# Math Blasterc
An educational, high-octane 3D arcade space shooter built with Three.js. Test your mental math reflexes while navigating through deep space and blasting asteroids that hold the correct answers to galactic equations.  

## 🚀 Features 
Immersive 3D Environment: Powered by Three.js with starfields, fog effects, and dynamic lighting.
Adaptive Difficulty: Math problems scale in complexity as you progress through levels (Addition, Subtraction, and Multiplication).
Cross-Platform Play: * Desktop: Aim with WASD/Arrows and fire with Space/Enter.
Mobile: Optimized for landscape mode with touch-to-shoot and gesture aiming.
PWA Ready: Includes a Web App Manifest and Service Worker for offline play and home screen installation.
Retro Audio: Web Audio API generated sound effects for lasers, explosions, and errors.
Visual Feedback: Dynamic crosshair, particle explosions, and HUD displaying score and hull integrity (lives).
##🛠️ Installation & Setup
Clone the project files:
index.html (Core game)
manifest.json (Web app configuration)
icon.png (App icon)
Run a Local Server:
Since the game uses Service Workers and specific module paths, it's best viewed through a local server.
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .


Open the Browser:
Navigate to http://localhost:8000/math-asteroids.html.
## 🎮 How to Play
Mission Objective
Destroy the asteroid displaying the correct answer to the equation shown at the top of the HUD.
Controls
Input
Action
Mouse / Touch
Tap/Click an asteroid to fire or move crosshair
WASD / Arrows
Precision Aiming
Space / Enter
Fire Laser

Scoring & Health
Correct Hit: +100 points (multiplied by level), advances to next wave.
Wrong Hit: -50 points.
Asteroid Collision: If an asteroid reaches your ship, you lose 1 Hull point.
Lives: You start with 9 Hull integrity points.
## 📱 Mobile Optimization
The game is designed to be played in Landscape Mode. If held in portrait, an orientation overlay will guide you to rotate your device for the best tactical view.
Created as an educational tool for sharpening math skills through gaming.
