# Quantum Games
These are all examples of games that I have added quantum computing elements to.

I will update the list as I make more.

## - Quantum Wormy:  

This code uses basic quantum and applies it to the game wormy.  I was inspired by [quantum battle ship](https://github.com/quantumjim/Battleships_with_complementary_measurements.git), the [accompanying tutorial](https://medium.com/@decodoku/how-to-program-a-quantum-computer-part-2-f0d3eee872fe) and [quantum catsweeper](https://github.com/desireevl/quantum-catsweeper).

I modified the game so that the worm wants to eat the red apples and avoid the blue apples (which are poisonous).

There are two apples in the game: the red are normal (+1 score) and the blue are special (+5 score or -3 score).  The blue apple is presented as a qubit.  If the qubit is measured as 1, +5 score.  If the qubit is measured as 0, -3 score.

I was going to use quantum to randomly generate the positions of the apples and of the snake with [ANU Quantum Random Number Generator](qrng.anu.edu.au), but it was too slow so I just used a normal random number generator.


