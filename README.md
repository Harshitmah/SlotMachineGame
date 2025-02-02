# SlotMachineGame
# Slot Machine Game in JavaScript & Node.js

A simple **Slot Machine** game built using **JavaScript** and **Node.js**. The game allows players to deposit money, place bets, spin the reels, and win based on matching symbols. It runs in the terminal using **prompt-sync** for user input.

## Features
- Deposit money before playing
- Choose the number of lines to bet on (1-3)
- Set a bet amount per line
- Spin the slot machine
- Check for winnings based on matching symbols
- Receive payouts for winning combinations
- Option to play again if balance remains

## How It Works
1. **Deposit Money**: The player enters an amount to start with.
2. **Choose Lines**: Select the number of paylines to bet on (1-3).
3. **Set Bet Amount**: Enter the amount to bet per line.
4. **Spin the Reels**: The game randomly generates a 3x3 grid with different symbols.
5. **Check Winnings**: If all symbols in a row match, the player wins based on predefined values.
6. **Update Balance**: Winnings are added to the balance.
7. **Play Again or Exit**: If the balance is above 0, the player can choose to continue or quit.

## Installation & Setup
### Prerequisites
- **Node.js** installed on your system
- **npm** (Node Package Manager)

### Steps to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/harshitmah99/slot-machine-game.git
   cd slot-machine-game
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the game:
   ```sh
   node project.js
   ```

## Dependencies
- **prompt-sync**: Used to take user input in the terminal.
  ```sh
  npm install prompt-sync
  ```

## Game Logic
- Uses `Math.random()` to simulate random spins.
- Checks if symbols match in selected paylines.
- Assigns payouts based on symbol values.
- Allows repeated play until the balance reaches zero.

## Example Gameplay
```
Enter a deposit amount: 100
Enter the number of lines to bet on (1-3): 3
Enter the bet per line: 5
You have a balance of $85
A | B | C
A | A | A  <-- Win!
C | D | B
You won, $25
Do you want to play again (y/n)? y
```

## License
This project is open-source and available under the **MIT License**.

---

Enjoy playing the Slot Machine game! 🎰

