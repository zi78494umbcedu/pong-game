An Arcade Pong Game with JavaScript @https://the-best-pong-game-here.netlify.app/

<img width="1023" alt="Screenshot 2024-07-22 at 2 09 49 AM" src="https://github.com/user-attachments/assets/7d960b9c-4763-40fe-9579-b63036f66a1b">
- Fun sound effects using Musiclab.
- Game logic breakdowns.
0. Game Area Perspective: How far from us: z-axis? (x, y, z):- rotate around z by scaling/shrinking around x, y
1. Start Game (isGameRunning:True/False)
2. If(Run)
    1. SET Timeout, every 8ms, frames for the ball every 8ms
3. WHEN DOES THE BALL HIT A PADDLE - keep track of ball position(x, y) and paddle position(x, y)
4. Paddle Update - altering padde speed by 1(limit to 5) and Y axis
5. similar the ball - initial speed and acceleration
6. figuring y2-y1 and x of the paddle for the ball to pass/hit

- Cool CSS transformations for our game board.Google Fonts
- Moving paddles and ball with key presses.
- Collision detection and high score tracking.
- Tools and Technologies Covered:
0. Version Control: GitHub for seamless collaboration and project management.
1. Github Desktop: Efficiently update repository with ease using Github Desktop.
2. Code Editor: Leveraged Visual Studio Code as primary code editor for enhanced productivity.
3. Deployment: Using Netlify, making it accessible to users worldwide.


