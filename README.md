Microsoft-Minesweeper-Solver
============================
"Microsoft Minesweeper (formerly Minesweeper) is a minesweeper computer game created by Curt Johnson, originally for OS/2, and ported to Microsoft Windows by Robert Donner, both Microsoft employees at the time. First officially released as part of the Microsoft Entertainment Pack 1 in 1990, it was included in the standard install of Windows 3.1 in 1992, replacing Reversi from Windows 3.0.[1] Microsoft Minesweeper has been included in all subsequent Windows releases until Windows 8. An updated version included in Windows Vista and Windows 7 was developed by Oberon Games.[2] Starting with Windows 8, Minesweeper is no longer included by default, although an app version of Microsoft Minesweeper developed by Arkadium is available on Windows Store." -<a href="http://en.wikipedia.org/wiki/Microsoft_Minesweeper">Wikipedia</a> 

note : The project is not completed yet.

This is the source code for the c# program I attempted to write to play the Microsoft Minesweeper game on windows 8, the game can be found on windows 8 store for free, unfortunately some parts of this project are hacked.

This is a video of the program in action on <a href="https://www.youtube.com/watch?v=Y-MWwAr0Kik">Youtube</a>.

The program follows these simple steps:
<ol>
<li>Take a screenshot of the game.</li>
<li>Exclude all unwanted parts from the screenshot.</li>
<li>Do some Image Processing to convert the game board image to a 2D array.</li>
<li>Do some logic to place mines and clear free tiles.</li>
<li>Free a random tile if the game reached a dead end.</li>
<li>Repeat the above till the program wins or loses.</li>
</ol>
