# CS-1D-final
Using the FPGA and our programmed ALU unit, we have come up with a simple game. 

The premise is that you’ve awoken in a labyrinth with no recollection of how you got there. Monsters are chasing you and you must run to survive. Avoid the walls and survive for as long as you can.

The game is displayed on an 8 by 8 led matrix, with the single lit led at the bottom row representing the player. More lit leds representing the walls come down from the top of the screen towards the player, if the player collides with them when they reach the bottom, the game is over. Over time, the walls will move faster and faster, increasing the difficulty of the game.

The controls are simple, the central red button to start the game and the green left and right buttons to move the player left and right respectively. The movement buttons can also be held down to move continuously and if the player reaches the end of the screen, they cannot move in that direction anymore.
