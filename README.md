# Digital-Snake-Ladder-Game
The project is to implement the snake ladder game digitally on both software and hardware using combinational and sequential logic circuits in a 4x4 LED Board and simulated on proteus including PCB design.


The snake ladder game is a classic board game played between two or more players. This is a game of chance means the outcome of the game is a random event determined by the roll of a dice. The goal of this game is to be the 
first to reach the ending square, usually 100, from the beginning square, 1. While snakes “eat” the player if met and send them back to a lower square, and ladders promote the player to a higher square. This project aims to 
design the game on a 4x4 LED grid. There will be a total of 16 positions, denoted with 0 through 15 in logic. Each position is visually represented by 4 LEDs. The first two for the players and the latter two for the snake 
and the ladder. We have chosen red and blue for player 1 and 2 respectively, yellow for the snake, and green for the ladder. A roll of dice, simulated by the dice module to generate a pseudo-random number from 1 through 3 
shifts the players’ position by that number. If a snake or a ladder is met, the player is demoted or promoted. The new 4-bit position of the player is stored in the memory and a player selector module is used to make 
players take turns to roll the dice. The player reaching the position 15 first wins the game. A win is determined by the winning module that compares the player’s current position to the winning condition. The win is then 
visually represented with buzzers and LEDs to notify the other player about the game result. There is also a reset module that can start the game all over from any position. 
