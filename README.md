# Tsukihime Trial Edition 1999 English
English translation project for Tsukihime's Winter Comiket Trial Edition released in 1999

![TSUKIMAKES - Translation Group](https://i.imgur.com/gHc6BWi.jpg)

## About
This is a translation patch for the Trial version Of Tsukihime found in the PLUS-DISC

## Project
Tsukihime (Trial Edition) is the first playable version of Tsukihime, first released during Comiket 57 (1999/12/24) in the form of 3.5″ floppy disks and later bundled in in Tsukihime's Half Moon Edition and Plus-Disc.
This project's goal is to patch, restore and translate the 767 lines of gamescript of the trial edition as well as its graphical assets into English

## Installation
- Grab the latest [Release ](https://github.com/Allunatik/Tsukihime-Trial-Edition-1999-EN-TL/releases) and follow the included installation instructions in the readme

## Credits

[Translation - Petrikow](https://github.com/Petrikow)
For their fine Translation work - Formatting

[Engine work - Playmer - ONScripter-Fork](https://github.com/playmer/ONScripter-EN-Official)
Thanks to Playmer for their work on bringing User Interface features to ONSCripter included in the Menubar and various other improvements

[Scripting - Formatting - Image Editing - Allunatik](https://github.com/Allunatik)
The projects Jack of all trades, it was a lot of fun working on all various sides of the project - managing it

[ONScripter-EN](https://github.com/Galladite27/ONScripter-EN)
And all involved with the original ONScripter that this project is based upon

### Special Thanks
To all involved supporting the project and bringing us all together, as well as Keripo and MoonlitArchives for helping with making sure there weren't changes made to the Trial over the many releases and bundles it had

## Build and DEV tools instructions

### Running the game

Add [ONScripter-EN](https://github.com/Galladite27/ONScripter-EN) to your [PATH](https://learn.microsoft.com/en-us/previous-versions/office/developer/sharepoint-2010/ee537574(v=office.14)) enviroment variable
- Place the file(s) in a folder in %USERPROFILE%\AppData\Local\ called "onscripter-en"
- Start > Advanced system settings > enviroment variables > path > edit > new > "%USERPROFILE%\AppData\Local\onscripter-en"> Ok

To run the game, execute the following command in the terminal
```onscripter-r```


Or the easy way grab [ONScripter-EN](https://github.com/Galladite27/ONScripter-EN) follow the instructions, grab the latest release and place it in the game's root folder, and run the game using the executable "onscripter-en.exe"


### Compile nscript

Add [ONScripter tools](https://kaisernet.org/onscripter/) to your [PATH](https://learn.microsoft.com/en-us/previous-versions/office/developer/sharepoint-2010/ee537574(v=office.14)) enviroment variable
- Place the file(s) in a folder in %USERPROFILE%\AppData\Local\ called "onscrtools"
- Start > Advanced system settings > enviroment variables > path > edit > new > "%USERPROFILE%\AppData\Local\onscrtools"> Ok

Execute the following command in the terminal
```nscmake -o nscript.dat nscript.txt```


### Decompile arc.sar
in the root folder execute
```sardec -o sar arc.sar```


### Compile arc.sar
In the decompiled sar folder execute
sarmake arc.sar *


### API
If you wish to know further what a piece of script does

https://kaisernet.org/onscripter/api/NScrAPI.html
