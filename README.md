# REATE-A-GRAPHICAL-SNAKE-GAME-USING-LIBRARIES-LIKE-SFML-OR-SDL.
A VISUALLY ENGAGING C++ GAME WITH SOUND EFFECTS AND INCREASING DIFFICULTY LEVELS.

COMPANY : CODTECH IT SOLUTION

NAME : MANAV AWANA

INTERN ID : CT04DN1135

DOMAIN : C++

DURATION : 4 WEEKS

MENTOR NAME : NEELA SANTOSH

DESCRIPTION :  
📝 Snake Game – Project Description
📌 Introduction
The Snake Game is a modern recreation of the classic arcade game, implemented in C++ using the SFML (Simple and Fast Multimedia Library) framework. This project combines fundamental programming concepts like object-oriented design, event-driven control, and multimedia handling to deliver a polished, interactive, and fun gaming experience. The game supports real-time graphics, sound effects, scoring, and keyboard interaction. It also demonstrates how a simple game can be enriched with modular architecture and external resources such as fonts and audio.

🛠️ Implementation Details
The game window is 800×600 pixels and is based on a grid system where each square block is 20×20 pixels. The player controls a green snake that moves continuously in one direction and can change direction using arrow keys. The main objective is to eat red food blocks that appear randomly on the screen. Each time the snake eats, it grows in size and the player’s score increases by one.

The application is organized into three core components:

1. Snake Class
This class encapsulates the logic related to the snake's body and behavior. It maintains a vector of sf::Vector2i objects representing the body segments. The move() function updates the snake’s head and tail positions. The grow() function uses a flag (growNext) to control when to extend the body. The class also handles wall collision and self-collision detection using simple comparisons.

2. Food Class
This class is responsible for generating food at random positions on the grid. It ensures that food does not spawn on the snake's body. After each successful food consumption, a new location is chosen using random number generation.

3. Game Loop (main() function)
The main() function is the heart of the game, managing rendering, input processing, collision checks, and score display. It creates graphical objects using SFML's sf::RectangleShape and text using sf::Text. The score is displayed in the top-left corner, while a “GAME OVER” message appears at the center if the snake dies. The user can press the R key to restart the game without restarting the application.

🔊 Audio Features
The game includes two sound effects:

eat.wav – plays when the snake eats food.

gameover.wav – plays when the game ends due to collision.

These are loaded using sf::SoundBuffer and played with sf::Sound. Audio feedback enhances the user experience and adds a responsive feel to player actions.

🎮 User Interface & Controls
Arrow keys (↑ ↓ ← →) – Change snake direction.

R key – Restart the game after a collision.

Score – Shown in the top-left corner.

Game Over Screen – Centered text instructs the player to restart.

All assets (arial.ttf, eat.wav, gameover.wav) must be in the same directory as the executable (snake.exe) for proper functionality.

🧾 Conclusion
This Snake Game project is a well-rounded example of applying C++ programming with SFML to build an engaging game. It demonstrates core concepts like object-oriented design, input handling, rendering, and sound integration. The code is modular and extensible, making it ideal for beginner game developers and students learning multimedia programming. With the addition of scoring, sound, and restart features, the game offers both fun and learning in a classic package.

OUTPUT : https://github.com/user-attachments/assets/3bf0c43d-4739-4c5d-bb9a-6eed31b1e5d1
