# pong-game

Description:
This project is a two‑player Pong game created in Python using the Pygame library.
It includes a save/load system using JSON files, multiple difficulty modes, and 
customizable gameplay settings such as ball size, ball speed, paddle length, 
paddle speed, and respawn countdown. Players control paddles on opposite sides 
of the screen and try to score points by getting the ball past the opponent’s paddle.

How to Install and Run the Program:
- Install Python 3.12 or older versions (Pygame supports up to 3.12)
- Install Pygame by running the following command in a terminal or command prompt:
    pip install pygame
- Download the game file and place it in any folder.
- Run the game by navigating to the folder and opening the file

How to Use It:

• When the game starts, you will see the save menu. You can choose:

- New Save – create a new score file
  
- Load Save – load an existing score file
  
- Settings – customize gameplay

• If you choose New Save or Load Save, you will be asked to type a filename. 
    Scores are saved automatically after each round.

• The Settings Menu allows you to change:

– Ball size

– Ball speed

– Paddle length

– Paddle speed

– Respawn countdown

• After choosing or loading a save, you will select a difficulty:

– Easy

– Medium

– Hard

– Custom (uses changes made in settings)

• Controls:

Player 1 (Blue): W = up, S = down

Player 2 (Red): Up Arrow = up, Down Arrow = down

Press E on the start screen to begin the round.

• Gameplay:

– The ball bounces off walls and paddles.

– If the ball passes a paddle, the other player scores.

– A countdown appears before the next round.

– Scores are saved to a JSON file automatically.
