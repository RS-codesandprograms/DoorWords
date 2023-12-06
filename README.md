# DoorWords

## Overview
This document describes requirements for the software implantation of DoorWords. This software will allow one person to play this memory game against himself. A description of the game plus the requirements of this implementation is provided below.

## The Game
When the game starts, the mystery word is generated. The user will be presented with a set of unique doors. Behind each door is one of the letters of the word. Users can view the scrambled letters one at a time by opening each door. Doors are opened and closed by clicking on them. After all the letters are viewed, the user will be shown the unknown word. The user will be prompted to spell out the word by clicking the doors in the correct letter order of the word. 
If the player gets a word right, he gets a correct point, otherwise known as a key (Found on the character map – font: Webdings,  character code: 0xD1).
If the player gets the word wrong, he gets an incorrect point, otherwise known as a lock  (Found on the character map – font: Webdings,  character code: 0xCF). 
Player wins at 5 keys or loses at 5 locks, whichever comes first.
The player can also pick how many doors will be active in each game. This determines how long the word will be. The options are four to eight. 

**The full spec for the game is in the repo ...**


![DoorWords](https://github.com/RS-codesandprograms/DoorWords/assets/94880497/7c16b80c-bd28-4707-bd05-a0761d20f127)



