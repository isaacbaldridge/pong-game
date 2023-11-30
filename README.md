# Welcome to Pong!

## How to Play

### Controls

#### Left Paddle (P1)
Move up: w key

Move down: s key


#### Right Paddle (P2)
Move up: Up arrow key

Move down: Down arrow key


### Game loop
- The ball gets slightly faster in the y-direction every time it collides with the top and bottom borders, and slightly faster in the x-direction every time it collides with one of the paddles.
- Points are scored by hitting the ball to the opposite end of the screen before the other paddle can hit the ball back.
- After a point is scored:
    - The ball's location is reset to the center of the screen.
    - The ball's speed is reset to the default speed.
    - The ball's x and y direction are reversed from directions is was moving when the point was scored.
        - Ex: If it was moving upwards and to the right when the point was scored, then it will be moving downwards and to the left when it resets to the middle of the screen.
    - A point is scored to the player opposite the side that the ball touched.

## Set-Up
0.) Ensure that you have [Python installed](https://realpython.com/installing-python/#how-to-install-from-the-full-installer) on your machine.

**OR**

Play the game on my [Replit](https://replit.com/@baldridgela/pongpy#pong.py).

1.) Fork the repo and clone it down using the SSH key. Copy and paste code below in your preferred directory in your terminal.

`git clone git@github.com:isaacbaldridge/pong-game.git`

2.) Run the pong.py file.

3.) A window containing the game should appear.

4.) In the case of an error reading that Tkinter module not found, run the following command in the terminal.
`sudo apt-get install python3-tk`

5.) Repeat step 2.
