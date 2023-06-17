# WORMY
## Video Demo:
<https://youtu.be/veV9kKv3_EE>

## Description:
Wormy is a classic arcade game in which the player controls a snake that moves around the playing field. The goal of the game is to eat as much food as possible so that the snake increases in size, and avoid collisions with walls or your own body.

### The main algorithm of the game "Wormy" has the following structure:

#### Initialization:
- Creation of game window and playing field.
- Creating a snake at the starting position.
- Placing food in a random position.

##### The main cycle of the game:
1. Receiving input from the player to control the snake (eg using the arrow keys).
2. Moving the snake in the selected direction.
3. Checking the condition of contact with the walls or with your body. If the condition is met, the game ends.
4. Checking the condition of eating food. If the snake eats food, it increases in size and the player gets points. Then a new food is created at a random position.
5. Updating the playing field and displaying the new state of the game.

##### Ending the game:

6. After the end of the game, display a message about the player's final score.
7. Clear resources and close the game window.


### The Python game "Snake" can have various features that make it unique. Here are some possible features that could be added to the game:

- Multiple Difficulty Levels: Add the ability to select a difficulty level, where each level has its own snake speed, obstacle placement, or other parameters that make the game more enjoyable for the player.

- Bonuses and Traps: Add bonus and trap elements to the playing field. For example, some products can give temporary enhancements, such as snake acceleration or temporary invulnerability to an obstacle. Traps, on the other hand, can slow down a snake or reduce its size.

- Save records: Save and display a player's best score. Players can try to beat their own record or compete with other players.

- Multiplayer: Add the ability to play Snake with other players over the network. This can create a competitive atmosphere where players compete with each other for the highest score or can interact on the playing field.

- Variety of looks: Give players the option to choose from different game themes or skins. For example, change the colors, background images or even stylize the snake and the playing field.

- Sound Effects: Add sound effects for various events in the game, such as eating food, hitting obstacles, or reaching a new record. Sounds can improve game immersion and add more fun for players.
