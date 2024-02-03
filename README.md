# Brain Test

Brain Test is a C++ console game that challenges your mental math skills and reaction time. The game generates random rectangles and asks you to calculate their area within a limited time. You can play up to five rounds and see your score at the end. This is a fun and simple way to train your brain and improve your math abilities.

## How it works

The game uses the following libraries and functions:

- `<iostream>` for input and output operations
- `<stdlib.h>` for random number generation and system commands
- `<unistd.h>` for sleep function
- `<time.h>` for time-related functions

The game defines and initiates the following variables:

- `m_trial` and `n_trial` for the maximum and current number of rounds
- `score` and `g_timeout` for the user's score and the time limit for each round
- `width` and `length` for the dimensions of the rectangle
- `area` and `user_area` for the correct and user-entered area of the rectangle
- `table_size` for the maximum size of the rectangle
- `user_stime` and `user_timeout` for the start time and elapsed time of the user's input

The game follows these steps:

1. Print the game instructions and wait for the user to press enter
2. Generate a random rectangle and draw it on the console
3. Ask the user to enter the area of the rectangle
4. Compare the user's answer with the correct answer and the time limit
5. Update the score and the number of rounds
6. Clear the screen and wait for the next round
7. Repeat steps 2-6 until the maximum number of rounds is reached
8. Print the game over message and the final score

## How to run

To run the game, you need a C++ compiler and a terminal. You can use any IDE or code editor of your choice. Here are the steps to compile and run the game on a Linux terminal:

- Navigate to the directory where the source code file `brain_test.cpp` is located
- Compile the code using the command `g++ brain_test.cpp -o brain_test`
- Run the executable file using the command `./brain_test`
- Enjoy the game!
