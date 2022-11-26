# OlsenG_BellC
## HW1
### Playing the Game
The game packaged for development has a required file too large for GitHub.

To play the game in full in the UE5 editor, you must start by opening the Main_Menu level if it is not already open. 

In the main menu, you have the options to start the game from the beginning, continue a previously started game (not available on first run or after a full playthrough is completed), change the current keybindings for the controls (under the options button), and to quit the game. The current high score of the game is also displayed here.

The goal of the game is to navigate the various mazes and obstacles and reach a gold/yellow platform at the end while collecting coins for points.
While the levels don't change based on the difficulty, the risk/reward of collecting coins will change according to the following:
- Easy: 5 lives, 8 hit points per life, and 5 points per coin
- Normal: 3 lives, 4 hit points per life, and 10 points per coin
- Hard: 1 life, 2 hit points per life, and 15 points per coin

During gameplay, there is a pause menu where you can choose to edit the key bindings, continue playing, or to save and quit to the main menu.
At the end is a results screen showing your score, the current high score (could be yours), and options to replay the game or to return to the main menu.
On death is a Game Over screen where you can choose to retry the level or to return to the main menu (saving your progress from the start of the level).

### Controls
Primary
- W: Roll forward in direction of camera
- S: Roll backwards towards the camera
- A: Roll left
- D: Roll right
- Space Bar: Jump
- Left Shift: Stop rolling (halts all movement)
- Mouse: Moves camera around player
- P: Pause the game

Secondary
- Up arrow: Roll forward in direction of camera
- Down arrow: Roll backwards towards the camera
- Left arrow: Roll left
- Right arrow: Roll right
- Right Control: Jump
- Numpad 0: Stop rolling (halts all movement)