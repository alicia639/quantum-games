# Quantum Games
These are all examples of games that I have added quantum computing elements to.

I will update the list as I make more.\

To play, download the .ipynb notebook and run all as a jupyter notebook.

## Quantum Wormy:  

This code uses basic quantum and applies it to the game wormy.  I was inspired by [quantum battle ship](https://github.com/quantumjim/Battleships_with_complementary_measurements.git), the [accompanying tutorial](https://medium.com/@decodoku/how-to-program-a-quantum-computer-part-2-f0d3eee872fe) and [quantum catsweeper](https://github.com/desireevl/quantum-catsweeper).  The game wormy comes from [here](https://inventwithpython.com/pygame/chapter6.html).

I modified the game so that the worm wants to eat the red apples and avoid the blue apples (which are poisonous).

There are two apples in the game: the red are normal (+1 score) and the blue are special (+5 score or -3 score).  The blue apple is presented as a qubit.  If the qubit is measured as 1, +5 score.  If the qubit is measured as 0, -3 score.

I was going to use quantum to randomly generate the positions of the apples and of the snake with [ANU Quantum Random Number Generator](qrng.anu.edu.au), but it was too slow so I just used a normal random number generator.

## Quantum Flood It:

This game follows along with the game flood it (based off ink spill) from [here](https://inventwithpython.com/pygame/chapter10.html).

The landscape is randomly generate with [ANU Quantum Random Number Generator](qrng.anu.edu.au).  It is a bit slow, but other than taking a long time to load, it does not affect the game.


## Electroquantum

This is a game I came up with itself.  The instructions of the game are fround in the game itself.

The purpose of this game is to introduce children to the uncertainty associated with electrons as well as the elements periodic table.  

I use a quantum circuit to randomly decide if the electron moves when the player approaches - which mimics the uncertainty principle associated with electrons.


