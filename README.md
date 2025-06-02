Astro Cards is a 2D educational arcade game where you blast enemies and master flashcards — all in real time. Created from scratch, this project blends the intensity of a Space Invaders-style shooter with the challenge of learning, making it perfect for students, developers, or educators who love games with purpose.

How to Play:
- Use ARROW KEYS to move left or right
- Quickly double tap either the left/right arrow to dodge
- Press SPACEBAR to fire lasers
- When a flashcard appears, type your answer and press ENTER or click submit.
- Answering correctly rewards you with health and score!
- You can create your own flashcards before starting the game or load an existing flashcard set from a .txt file (assuming you've already created one in-game)

Development Note:
Astro Cards was developed entirely in Java Swing, with no external game engine. The game logic, rendering, input handling, and UI were all implemented manually using the following Java standard libraries:
- Swing
- AWT
- Image & BufferedImage
- Util (ArrayList, List, Random)
- IO (For file saving/loading)
- Sound.sampled
- Swing.Timer

Personal Statement:
I built Astro Cards without a game engine because I wanted to truly understand what happens under the hood when you draw a sprite, move a character, or animate a scene. This project represents my deep dive into game development fundamentals — managing frame timing, pixel-based positioning, and real-time rendering using only Java Swing. I learned a lot, including how graphics are rendered at a fundamental level - from manually positioning sprites with pixel coordinates to managing screen repaints and timing using Java's built-in rendering pipeline. I wrote my own collision logic, movement systems, UI handling, bullet firing, and even audio playback. This project pushed me in many ways, making me think critically on how I can apply mathematics to build a strong engine. I highly recommend that anyone curious about game development try building something without an engine — you'll gain a deeper understanding of how games really work.
