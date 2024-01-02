# DoorWords

## Overview
This document describes requirements for the software implementation of DoorWords. This software will allow one person to play against himself. A description of the game plus the requirements of this implementation is provided below.

## The Game
When the game starts, the mystery word is generated. The user will be presented with a set of unique doors. Behind each door is one of the letters of the word. Users can view the scrambled letters one at a time by opening each door. Doors are opened and closed by clicking on them. After all the letters are viewed, the user will be shown the unknown word. The user will be prompted to spell out the word by clicking the doors in the correct letter order of the word. 
If the player gets a word right, he gets a correct point, otherwise known as a key   (Found on the character map – font: Webdings, character code: 0xD1).
If the player gets the word wrong, he gets an incorrect point, otherwise known as a lock  (Found on the character map – font: Webdings, character code: 0xCF). 
Player wins at five keys or loses at five locks, whichever comes first.
The player can also pick how many doors will be active in each game. This determines how long the word will be. The options are three to eight. 

**The full spec for the game is in the repo ...**




![image](https://github.com/RS-codesandprograms/DoorWords/assets/94880497/c07d6c9f-5f7e-4aeb-80e8-6acbe6344e00)




