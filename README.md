# Simon Game: Test Your Attention

This project is an online version of the classic "Simon" game, developed using JavaScript, HTML, and CSS. The game tests the player's memory through an increasing sequence of colors, which must be repeated in the correct order. With each level, the Simon Game becomes more challenging, adding a new color to the sequence and requiring heightened focus to remember longer patterns.

## How the Game Works

### Starting the Game
The game begins when any key is pressed. The initial level is displayed on the screen, and the game generates the first random sequence of colors.

### Creating the Sequence
At each level, a new color is added to the previous sequence. Each color is displayed with a light effect and a specific sound, creating a unique sequence for each round.

### Player’s Response
The player must memorize the sequence and reproduce it by clicking the colored buttons. Each correct click is accompanied by a sound and a button animation, providing immediate feedback to the player.

### Verifying the Player's Input
- After each button press, the game checks if the player's sequence matches the generated one.
- **Correct Input:** The player advances to the next level, and the sequence is extended with a new color.
- **Incorrect Input:** The game plays an error sound, displays a "Game Over" message, and prompts the player to press any key to restart.

## Technologies Used
- **JavaScript** for game logic
- **HTML** for structuring the interface
- **CSS** for styling and animations

## How to Play
1. Clone the repository:
   ```bash
   git clone https://github.com/username/simon-game.git
   cd simon-game
