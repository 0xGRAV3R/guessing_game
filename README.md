# Rust Guessing Game | guessing_game
The program will generate a random integer between 1 and 100. It will then prompt the player to enter a guess. After a guess is entered, the program will indicate whether the guess is too low or too high. If the guess is correct, the game will print a congratulatory message and exit.

The first part of the guessing game program will ask for user input, process that input, and check that the input is in the expected form. To start, we’ll allow the player to input a guess. 

Second is add the rand generator and allow the system to println! it

Third create a comparison between the random number generated () with the number input from user using --> use std::cmp::Ordering;

Need to also convert string to u32 integer

Then create a loop for the user to keep guessing until they get the correct answer