# Tsukihime Trial Edition 1999 English
English translation project for Tsukihime's Winter Comiket Trial Edition released in 1999

## About
Tsukihime (Trial Edition) is the first playable version of Tsukihime, first released during Comiket 57 (1999/12/24) in the form of 3.5″ floppy disks and later bundled in in Tsukihime's Half Moon Edition and Plus-Disc.

## Project
This project's goal is to patch, restore and translate the 767 lines of gamescript of the trial edition as well as its graphical assets into English

## Build and DEV tools instructions

Grab [ONScripter-EN](https://github.com/Galladite27/ONScripter-EN) follow the instructions, grab the latest release and place it in the game's root folder, and run the game using the executable "onscripter-en.exe"

Or add [ONScripter-EN](https://github.com/Galladite27/ONScripter-EN) to your [PATH](https://learn.microsoft.com/en-us/previous-versions/office/developer/sharepoint-2010/ee537574(v=office.14)) enviroment variable

-Start > Advanced system settings > enviroment variables > path > edit > new > "%USERPROFILE%\AppData\Local\onscripter-en"> Ok

To run the game, execute the following command in the terminal
```onscripter-r```

Compile nscript

Add [ONScripter tools](https://kaisernet.org/onscripter/) to your [PATH](https://learn.microsoft.com/en-us/previous-versions/office/developer/sharepoint-2010/ee537574(v=office.14)) enviroment variable

-Start > Advanced system settings > enviroment variables > path > edit > new > "%USERPROFILE%\AppData\Local\onscripter-en"> Ok

Execute the following command in the terminal
```nscmake -o nscript.dat nscript.txt```

## Translation cheat sheet
```
` Indicates the start of a English line
-@ Continue prompt - pauses until click - can @ chain @ multiple on the same line
-br - add empty line - i.e if adding spaces between two rows of text
-\ page break (also works as a continue prompt) -  new blank page
- "" Quotation marks need to be replaced with ` `
- --- or ---- replace em lines, depending on their length
-JP Full width spaces - 2x EN half width spaces, if mimicking long "pauses" add enough to fill space roughly
-Max character count before a break: 745~
- Lines: 15 (Absolute max)```
```

**API**
If you wish to know further what a piece of script does
https://kaisernet.org/onscripter/api/NScrAPI.html
