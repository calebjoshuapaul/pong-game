# pong-game

https://calebjoshuapaul.github.io/pong-game/



   - The code starts by creating a new Ball object and then creates two Paddle objects.
   - The first is for the player, and the second is for the computer.
   - It also creates an element to hold their scores in.
   - The update function will be called every time there's a change in time (i.e., when it changes from 0 seconds to 1 second).
   - In this case, it checks if lastTime has been set before calling itself with delta as its argument.
   - If so, it calculates how much time has passed since lastTime was set and updates the score accordingly using document query selectors that are created specifically for this purpose: one for each player's score and one for each computer's score.
   - The code is an example of a function that will update the score.
   - The first line creates a variable called lastTime, which is used to keep track of the time in milliseconds.
   - The second line checks if there is already a value for lastTime, and if so it subtracts delta from it.
   - The code starts by creating a ball and then sets the x-coordinate to be 0.
   - The code then creates a computer paddle, which is set to have an initial position of (0,0) and an initial angle of 0 degrees.
   - The code then updates the computerPaddle with delta time steps so that it moves towards the ball in increments of 1 degree per update step.
   - The next line calculates the hue value for this particular frame using getComputedStyle() .
   - It uses parseFloat() to convert this value into a number between 0 and 360 degrees.
   - Then it changes the color property on documentElement from --hue=255 to --hue=360 + delta * 0.01 , where delta is calculated as one degree per update step taken by computerPaddle .
   - The code is written in a way that the computer paddle is updated with the ball's movement and then it updates itself.
   - The computerPaddle.update(delta, ball.y); function sets the position of the computer paddle to be equal to the ball's current position minus its previous position plus delta * 0.01
   - The code starts by declaring variables for the ball and player paddle.
   - The variable "time" is used to keep track of how long it has been since the game started.
   - The function handleLose() is called when the user clicks on the lose button in order to reset both players' paddles and score.
   - The code is an example of how to implement a game of Pong.

