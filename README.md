🐍 Snake Game
Hey! Welcome to my Snake game! It’s a fun, old-school game where you move a snake to eat red fruit and grow longer. I made it with C++ and SFML. The play area is a 30x20 grid, and if you hit your tail, your snake gets shorter but keeps going. The edges wrap around, so you pop out on the other side. Great for playing or messing with the code!
   What’s the Game?
You steer a snake with arrow keys to grab fruit. Each fruit makes your snake longer. Hit your tail? You shrink but don’t lose. The world loops, so no crashing into walls. It moves 10 times a second, so it feels smooth.
   How to Play It
Stuff You Need

A C++ compiler (like GCC or Visual Studio).
SFML (get it at sfml-dev.org).
Two tiny pictures:
white.png: A 16x16 white square for the background.
red.png: A 16x16 red square for the snake and fruit.(No pictures? Make them in Paint—just 16x16 squares!)

Steps to Start

Get the code:git clone https://github.com/avinam thakur/snake-game.git
cd snake-game

Grab SFML:
Windows: Check SFML’s guide.
Linux: Type sudo apt-get install libsfml-dev.
Mac: Use brew install sfml.

Add pictures: Put white.png and red.png in an images folder.
Build it:g++ -c main.cpp -I/path/to/sfml/include
g++ main.o -o snake -L/path/to/sfml/lib -lsfml-graphics -lsfml-window -lsfml-system

Play: Run ./snake (Linux/Mac) or snake.exe (Windows).

 How to Play

Move: Use ⬅️ ➡️ ⬆️ ⬇️ arrows. Close the window to quit.
Goal: Eat red fruit to grow. Hit your tail, and you shrink but keep playing.
Trick: Use the looping edges to dodge your tail!

 Little Problems

Fruit might appear on your snake (free point!).
The snake starts in a random spot and might move weird at first.
Turning back (like right to left) can make you shrink quick.

 Cool Ideas

Add a score to count fruit.
Show “Game Over” if you crash.
Stop fruit from popping up on the snake.
Add sounds for eating or hitting.

 Help Out
Got a fun idea? Copy the repo, change the code, and share it back! Try adding a score, new pictures, or a pause button. Make a branch (git checkout -b my-idea), save your work, and send a pull request.
 What’s in Here

main.cpp: The game’s code.
images/white.png: White square for the grid.
images/red.png: Red square for snake and fruit.

 Thanks
Huge thanks to SFML for making this easy and to the classic Snake game for the fun vibes!
 Chat with Me
Got ideas or questions? Post on GitHub Issues.
Have fun slithering! 🐍
