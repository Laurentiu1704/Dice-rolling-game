# Dice Rolling Script

This simple Python script simulates rolling two six-sided dice. It repeatedly prompts the user to decide whether they want to roll the dice or exit the program.

## How It Works

1. The program enters an infinite loop using `while True`.
2. The user is asked whether they want to roll the dice by typing `y` (yes) or `n` (no).
3. If the user chooses `y`:

   * Two random integers between 1 and 6 are generated.
   * The results are displayed as a pair of values, representing the faces of two dice.
4. If the user chooses `n`:

   * The program prints a closing message and exits the loop.
5. Any other input results in an "Invalid choice" message and the loop continues.

## Requirements

* Python 3.x
* No external libraries are needed; it uses Python's built-in `random` module.

## How to Run

1. Save the script to a file, for example, `dice.py`.
2. Open a terminal or command prompt.
3. Run the script using:

   ```bash
   python dice.py
   ```
4. Follow the on-screen prompts to roll the dice.

## Example Output

```
Roll the dice? (y/n): y
(4, 2)
Roll the dice? (y/n): y
(6, 1)
Roll the dice? (y/n): n
Thanks for playing!
```
