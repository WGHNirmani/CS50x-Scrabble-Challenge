# CS50x-Scrabble-Challenge
Complete the implementation of scrabble.c, such that it determines the winner of a short scrabble-like game, where two players each enter their word, and the higher scoring player wins.

Stored the point values of each letter of the alphabet in an integer array named POINTS.

For example, A or a is worth 1 point (represented by POINTS[0]), B or b is worth 3 points (represented by POINTS[1]), etc.

Created a prototype for a helper function called compute_score() that takes a string as input and returns an int. Whenever we would like to assign point values to a particular word, we can call this function. Note that this prototype is required for C to know that compute_score() exists later in the program.

In main(), the program prompts the two players for their words using the get_string() function. These values are stored inside variables named word1 and word2.

In compute_score(), your program should compute, using the POINTS array, and return the score for the string argument. Characters that are not letters should be given zero points, and uppercase and lowercase letters should be given the same point values.

For example, ! is worth 0 points while A and a are both worth 1 point.

Though Scrabble rules normally require that a word be in the dictionary, no need to check for that in this problem!

In main(), your program should print, depending on the players’ scores, Player 1 wins!, Player 2 wins!, or Tie!.
