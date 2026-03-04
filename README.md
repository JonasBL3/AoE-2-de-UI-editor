# AoE-2-de-UI-editor
This ui editor lets you import, edit and export .json files

This is very much an unfinished poject but may help someone get going. My app is made to make editing ui elemts easier, however, the way the game reads these files is not always as clear, so you'll have to do some trail and error. I may or ma not continue development. I used chat gpt 5.2 Thinking to make this.

the game builds the UI according to .json files which are stored in you games folder. for me that is here: C:\Program Files (x86)\Steam\steamapps\common\AoE2DE\widgetui
open the app, import a file, edit and eport it to the same folder. Your changes should apply to the game imediatly. the game wil default to ASIA panels, so play an asian civ like chinese when testing things out.

json file that will be most usefull are:
blankbottompanel
blanktoppanel
GameMsgPanel
mappanel
menupanel
resourcepanel
scorepanel
technologyprogresspanel
timerpanel
worldtimerpanel

there are some very odd behaviours. Here are some of them:
The tooltips dialog box cannot be moved
the anchorpoint of the backgroundright panel inside the command panel will always move to the top of the commandpanel.

After edditing the ui elements, you may also want to edit the graphisc, The game reads the grapics on startup and cant be changes after. the grapics are stored here: C:\Program Files (x86)\Steam\steamapps\common\AoE2DE\widgetui\textures\ingame\panels edit the png's inside the vic folder. You might want to create a canvas the same size as you made the background panel inside the ui editor.
