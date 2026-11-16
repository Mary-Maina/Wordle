Wordle Game in Go

About the Project

A command-line version of the popular Wordle word-guessing game, built using Go (Golang).

The objective is to guess a randomly selected five-letter secret word within six attempts.

This project is part of my journey learning Go, with a focus on applying concepts such as structs, slices, maps, pointers, functions, and error handling.

How to Play

1. The game randomly selects a five-letter word from a predefined word bank.

2. The player has six attempts to guess the secret word.

3. After each guess, the game provides feedback on the letters:

4. Green: Correct letter in the correct position.

5. Yellow: Correct letter in the wrong position.

6. Grey: Letter does not appear in the secret word.

The player wins by guessing the correct word within six attempts.

If all six attempts are exhausted, the game reveals the secret word.
