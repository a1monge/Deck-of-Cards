### Project: Deck of Cards in Go

This project implements a simple deck of cards in Go, providing functionality for creating, shuffling, saving, and loading a deck of 52 playing cards. It includes tests to verify the correctness of deck creation and file handling.

---

### Files Overview:

1. **deck.go**: 
   - Defines a custom type `deck` as a slice of strings representing the cards.
   - Implements several methods for the deck:
     - `newDeck()`: Creates a new deck with 52 cards (Ace to King of each suit).
     - `print()`: Prints each card in the deck.
     - `deal()`: Deals a hand of cards by splitting the deck into two parts.
     - `toString()`: Converts the deck into a comma-separated string.
     - `saveToFile()`: Saves the deck to a file.
     - `newDeckFromFile()`: Loads a deck from a file.
     - `shuffle()`: Shuffles the deck using a random source.

2. **deck_test.go**: 
   - Contains test functions for the deck:
     - `TestNewDeck()`: Tests the creation of a new deck by checking the number of cards and verifying the first and last card.
     - `TestSaveToDeckAndNewDeckFromFile()`: Tests saving and loading a deck from a file and verifies that the loaded deck has 52 cards.

3. **main.go**:
   - Initializes a deck of cards, shuffles it, and prints the shuffled deck.

---

### Usage:
- Run the tests to verify that the deck creation and file handling are functioning correctly.
- Use the main program to shuffle and print a deck of cards.
