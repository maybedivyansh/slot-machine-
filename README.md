Slot Machine Game
=================

A simple command-line slot machine game implemented in Python. This project demonstrates basic programming concepts such as user input handling, randomization, loops, and functions, while providing an interactive and fun experience.

---

## Key Features

- **Deposit System:** Users can deposit money to play the game.
- **Customizable Bets:** Choose the number of lines to bet on (up to 3) and the amount to bet per line.
- **Randomized Slot Machine:** The slot machine generates random symbols for each spin, simulating a real slot machine.
- **Winnings Calculation:** Automatically checks for winning lines and calculates winnings based on symbol values and bets.
- **Balance Tracking:** Keeps track of the user's balance throughout the game.
- **Input Validation:** Ensures all user inputs (deposit, bet, lines) are valid and within allowed ranges.
- **Replayable:** Users can spin as many times as they want until they choose to quit or run out of balance.

---

## How to Run

1. Make sure you have Python 3 installed.
2. Run the script:
   ```
   python slot_machine.py
   ```
3. Follow the on-screen prompts to deposit money, place bets, and spin the slot machine.

---

## Game Rules

- You can bet on 1 to 3 lines per spin.
- Each line bet must be between $10 and $100.
- The slot machine has 3 rows and 3 columns, with symbols A, B, C, and D, each having different frequencies and payout values.
- Winnings are calculated based on matching symbols across the lines you bet on.
- The game continues until you choose to quit or your balance runs out.

---

## Example Session

```
what would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $20
you are betting $20 on 2 . total bet is equal to : $40
A | B | C
B | D | A
C | C | D
you won $0.
you won on
current balance is $60
Press enter to spin (q to quit).
```

---

## Key Learnings

- **User Input Handling:** Validating and processing user input for a smooth user experience.
- **Randomization:** Using Python's `random` module to simulate slot machine spins.
- **Data Structures:** Using dictionaries to manage symbol counts and values.
- **Functions:** Modularizing code into reusable functions for clarity and maintainability.
- **Loops and Control Flow:** Managing game state and user interaction with loops and conditionals.
- **Error Handling:** Ensuring robust input validation and error messages.

---
