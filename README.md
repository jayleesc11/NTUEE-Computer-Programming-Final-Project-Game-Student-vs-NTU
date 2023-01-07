# NTUEE-Computer-Programming-Final-Project-Game-Student-vs-NTU
This game is a tower defense game based on the university school life of the developers.<br>
Players assume control of the Student side, taking defense against the NTU side which is controlled automatically by the program.

## For users:
### Window Size:
This game opens up a window of size 1100*960 pixels. Please modify your display settings to accommodate the window before you run the game.

### Starting Interface:
Open "Final_Project.exe".<br>
The starting interface pops up once the game is started. There are three blocks on the interface.<br>
Please click on the block labeled "New Game" to start playing. For information on the characters you control, please click on "Info on student side (player controlled)"<br>
For information on the characters, you will be taking defense against, please click on "Info on NTU side (CPU controlled)".<br>

### Properties of characters:
*Cost: *The resources (coffee) needed to construct a character on the map. The cups of coffee you possess are displayed at the left edge of the card bar.
Cooldown time: The minimum interval between constructing a character and selecting it the next time. The cooldown time remaining for each character is displayed over their position on the card bar in seconds.
Please note that cooldown time doesn't start counting until the character has been constructed on the map.
HP: The amount of damage a character can bear before it gets demolished.

Control:
Click on the character cards in the card bar located at the top left of the screen to select a character. 
The image of the character will move with your cursor once a character has been selected.
Then, click on any block in the game map to place the character on the chosen block. Your character is then constructed on the map and is ready to fight!
Please note that once a character has been constructed, it can no longer be moved to another position on the map.
If you want to cancel a character selection before construction, simply click on the card bar once more. 
You will see that the image of your character no longer follows your cursor on the screen.

Battle:
Once the characters have been constructed on the map, they will start causing damage to the nearest object of the NTU side. 
For the NTU side objects to cause damage on the student's side, the objects must be in direct contact with your characters.
Once a character's or an object's HP is damaged to zero by the opposing side, it is killed and demolished from the map.
NTU objects will move at a constant speed toward the left of the map until they meet a character of the student side. 
If they succeed in killing the character, they will resume movement toward the left.

Winning condition:
The game will be won once the object named FINAL on the NTU side has been demolished by the students' side.

Losing condition:
The game will be lost once an NTU object not of type "Mr.Shuiyuan" reaches the first column on the left of the map.
