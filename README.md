
# Ymir localisation

This is the localisation for Ymir.

Ymir is a 4X multiplayer strategy game combined with a city builder where each player develops a civilization of Pigmen starting at the stone age. 

More information here https://ymir-online.com/ or on steam https://store.steampowered.com/app/378360/Ymir

##  How to translate Ymir

- To support a new language, simply copy-paste the english directory and rename it with your new language.
It will then appear as a valid language option ingame.
- All text files must be kept encoded in UTF-8.
- I advise you to use a text editor like "Notepad++" to conveniently edit and control the encoding of the text files.
- Files contains text keys starting by the character #. The lines beneath are the text content matching that key, which is to be translated.
- Do not rename or modify the actual text keys.
- The text keys don't need to be in a specific order.
- If new text keys are added from a game update and missing from the translation files, they will be 
automatically added at the end of the files after launching the game once, making it convenient to maintain.
- When keys are missing, their content is copy pasted by default from the "parent language" defined in 
the "_language_setup.txt" file of the concerned language directory. It is "english" by default.
- The game fonts currently only supports the latin and cyrillic characters.

### LANGUAGE SETUP file

- font_scale: global scale factor applied to fonts, additionnally to the ingame size and scale factors for each ui. 1 is default.

- font_pos_x & font_pos_y: global position offset applied to all displayed fonts. nb of pixels for a size 10 font. 
applied proportionnally to the each text depending on its size to maintain the same proportional offset (so font_pos_x of 2 
means x+ 4pixels when displaying a font of size 20 )