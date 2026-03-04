# AoE-2-de-UI-editor
This ui editor lets you import, edit, and export .json files

This is an unfinished project, but it may help someone get going. My app was made to make editing UI elements easier; however, the way the game reads these files is not always clear, so you'll have to do some trial and error. I may or may not continue development. I used ChatGPT 5.2 Thinking to make this. Feel free to edit it and repost it yourself.

The game builds the UI from .json files stored in your games folder. For me, that is here: C:\Program Files (x86)\Steam\steamapps\common\AoE2DE\widgetui
open the app, import a file, edit and export it to the same folder. Your changes will apply to the game immediately. The game will default to ASIA panels, so play an asian civ like Chinese when testing things out.


JSON files that will be most useful are:

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


There are some very odd behaviours. Here are some of them:
The tooltips dialog box cannot be moved
the anchorpoint of the backgroundright panel inside the command panel will always move to the top of the commandpanel.


After editing the ui elements, you may also want to edit the graphics. The game reads the graphics on startup and can't be changed afterward. the graphics are stored here: C:\Program Files (x86)\Steam\steamapps\common\AoE2DE\widgetui\textures\ingame\panels edit the png's inside the vic folder. You may want to create a canvas the same size as the background panel you made inside the ui editor.

I'll also provide one of my mods as an example. You can import it into the app and learn a thing or two from it.
