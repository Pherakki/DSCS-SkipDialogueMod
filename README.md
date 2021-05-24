# DSCS-SkipDialogueMod
A mod to fast-forward dialogue in Digimon Story: Cyber Sleuth. This mod currently only affects dialogue. This means that cutscenes and movies, such as the "new game" sequence, are not currently affected.

## Features
- Toggle accelerated dialogue by pressing the appropriate "Cancel" button for your input device (_e.g._ `Circle` for Dualshock controllers, `B` for XBOX, etc.) 

## Planned Features
- Animation acceleration in cutscene-style dialogues [requires expansion of mod manager features]
- Cutscene acceleration [requires expansion of mod manager features]
- Movie Skipping [May not be possible]

## Installation
1. Download the latest release.
2. Register the mod in [SimpleDSCSModManager](https://github.com/Pherakki/SimpleDSCSModManager) by dragging-and-dropping the mod zip archive onto the left-hand pane ("mod activation window") of SimpleDSCSModManager.
3. Click "Finish" in the pop-up registry wizard. Wait for the mod manager to finish registering the mod.
4. Tick the checkbox next to the mod to activate it. Click "Install Mods"
5. Wait several minutes for the mod manager to patch everything together and cache the results for faster installs next time you edit the files.
6. Click "Launch Game", or launch the game normally.

## Modifying the text speed
If the text speed is too fast or too slow, you can go into `modoptions/scriptfuncs.txt` and change the numbers `globalSkipTextSpeed` and `globalSkipTextSpeed2`. Increasing these numbers will increase the time that each message is displayed for before auto-advancing to the next message. `globalSkipTextSpeed` affects the time that messages are displayed in cutscene-style dialogues, and `globalSkipTextSpeed2` affects the time that messages are displayed in "NPC-interaction"-style dialogues. If this second number is set much lower, "NPC-interaction"-style dialogue messages may not display at all, so be careful.
After you've made your changes, remember to right-click the mod in SimpleDSCSModManager and click "Re-install..." in the context menu to re-generate the necessary mod files. Then, click "Install Mods" again in SimpleDSCSModManager to install the new files to the game.
