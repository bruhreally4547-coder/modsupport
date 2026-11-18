1. download the zip file and extract it
2. place the 'Vee' folder in users/(your name)/AppData/Local/Frickbears3/addons
3. replace the data.win file in the game's folder with the data.win file in this mod's folder. this is the place for the custom dialogue background music and a completely custom dialogue speaker


if you wish to simply add the assets from the data.win file (in order for it to work with other mods), you need UndertaleModTool (or other programs similar), though this will somewhat reveal spoilers for the things in this mod in particular


1. for the songs, open the data.win file, find the songs marked as '(CUSTOM)' and find its .ogg file. simply export the songs and import them into your preferred data.win file

2. as for the custom dialogue speaker, ADD THIS TEXT TO gml_Object_oTextBox_Create_0:
                 if (Speaker == "Astro")
                    Talksound = voc_tsAstro;
PLACE IT RIGHT BELOW THE STRINGS FOR THE BOSS
FIND 'voc_tsAstro.ogg' AND PLACE IT IN THE DATA.WIN FILE