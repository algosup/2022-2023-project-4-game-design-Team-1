#### ➡️ Click [here](https://github.com/algosup/2022-2023-project-4-game-design-Team-1/blob/main/README.md) to go to the README file

# Functional Specifications

<img src="https://avatars.githubusercontent.com/u/71769486?v=4" width="150">

#### [**`Théo Trouvé`**](https://github.com/TheoTr)

###### *Program Manager*

<details>
<summary style="font-size:150%">
  📖 Table of Contents
</summary>

- [Functional Specifications](#functional-specifications)
      - [**`Théo Trouvé`**](#théo-trouvé)
          - [*Program Manager*](#program-manager)
  - [Mind Maze: Jail Escape Edition](#mind-maze-jail-escape-edition)
    - [Theme](#theme)
    - [Potatoe](#potatoe)
      - [1. Character](#1-character)
      - [2. Inventory](#2-inventory)
      - [3. Game Mechanics](#3-game-mechanics)
      - [4. User Interface](#4-user-interface)
      - [5. Menu](#5-menu)
      - [6. Help](#6-help)
      - [7. Sound](#7-sound)
      - [8. Save](#8-save)
      - [9. Enigmas](#9-enigmas)
        - [9.1 Buttons](#91-buttons)
        - [9.2 Statues](#92-statues)
        - [9.3 Piano](#93-piano)

</details>

## Project Title: *Mind Maze: Jail Escape Edition*

### Theme

- Character
- Inventory
- Game Mechanics
- User Interface
- Menu
- Help
- Sound
- Save
- Enigmas

#### 1. Character

- First Person
- Choose your name

#### 2. Inventory

- 'I' to open inventory
- Able to see the objects in the inventory
- Select an object in the inventory to move it in the shortcut
- Put object in inventory from shortcut

#### 3. Game Mechanics

- Move with 'Z', 'Q', 'S', 'D'
- Run with 'Shift'
- Jump with 'Space'
- Grab an object with 'Left Click'
- Interact with an object like door, etc...
- Able to interact with objects in his hand like keys, flashlight, etc...

#### 4. User Interface

- Inventory shortcuts (with 3 spaces)
- Ability to change the object in the shortcut with the mouse
- Ability to interact with the object in the shortcut/hand
- Ability to switch between the object in the hand and the object in the shortcut with the mouse wheel

#### 5. Menu

- Launch screen
  - Play button
  - Settings button
  - Credits
- In game
  - Pause button with 'Escape'
    - Settings button
    - Ability to leave and return to the menu

#### 6. Help

- Help button, to see all shortcuts
- Clues to help the player after an amount of time

#### 7. Sound

- Add sound during specific events (like when the player is near a guard, near to solve a puzzle, etc...)
- Add music during the game
- Add menu to change the volume of the music and the sound effects or cut them off

#### 8. Save

- Save the game
- Checkpoint system after each puzzle

#### 9. Enigmas

- To finish the game, the player has to solve 3 puzzles:
  - Buttons
  - Statue
  - Piano

##### 9.1 🔸 Buttons

- The player has to press the buttons in the right order to open the door, there is 5 buttons in the room and 5 colors (Red, Blue, Green, Yellow, Purple).
- The player need to find that the last letter of each word correspond to the color and the order [**Map**, **Warthog**, **Blob**, **Gray**, **Floor**]. If the player is too long to find the trick we’ll give him a clue like a sentence to help him.
- The solution is to click on the buttons in the order : [**Purple , Green , Blue , Yellow , Red**].
- Once the player will get the code, he could escape the first room.

##### 9.2 🔸 Statues

- Different statue parts across the jail need to be found to build the statue and discover a secret message.

- After assembling the statue, the player will receive a coded message that you will need to decipher. To decipher the message, you will need to find a piece of paper in the room. This piece of paper will translate the symbols on the statue.

- Once the player will get the code, he could escape the second room.

##### 9.3 🔸 Piano

- The player has to play a piece of piano to open the door.
- If he plays a wrong note, he will need to restart from scratch.

##### 9.4 🔸 Between each puzzle, the player will have to escape guards

- The player will have to find a way to distract the guard and escape go to the next room.
- If the player is seen by the guard, he will have to restart from the beginning of the puzzle.
- The player need to redo all the way to recome back to the room where he was seen by the guard.
